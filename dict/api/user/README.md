# User

## Operations

### userCreate

```http
POST /createUser
```

UserCreate

### deleteUser

```http
DELETE /deleteUser/{Topicid}
```

deleteUser

### getUser

```http
GET /getUser
```

GetUser

### updateUser

```http
PUT /UpdateUser/{Topicid}
```

UpdateUser

## Implementation

This is an example of the API implementation to use to update the actual API implementation
when the API structure has changed.

```typescript
async function userCreate(request: Api.BODYDATA | undefined): Promise<t.UserCreateResponse> {
	throw 'Unimplemented'
}

async function deleteUser(topicid: string): Promise<t.DeleteUserResponse> {
	throw 'Unimplemented'
}

async function getUser(): Promise<t.GetUserResponse> {
	throw 'Unimplemented'
}

async function updateUser(topicid: string, request: Api.BODYDATA | undefined): Promise<t.UpdateUserResponse> {
	throw 'Unimplemented'
}


const api: t.UserApi = {
	userCreate,
	deleteUser,
	getUser,
	updateUser,
}

export default api
```
