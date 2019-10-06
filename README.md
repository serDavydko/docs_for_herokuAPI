# hobbies API endpoints v0.0.1



- [Hobbies](#hobbies)
	- [Create hobbies](#create-hobbies)
	- [Delete hobbies](#delete-hobbies)
	- [Retrieve hobbies](#retrieve-hobbies)
	- [Update hobbies](#update-hobbies)
	
- [Users](#users)
	- [Create users](#create-users)
	- [Delete users](#delete-users)
	- [Retrieve users](#retrieve-users)
	


# Hobbies

## Create hobbies



	POST /hobbies


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| hobby			| 			|  <p>Hobbies's hobby.</p>							|
| passion			| 			|  <p>Hobbies's passion.</p>							|
| sinceYear			| 			|  <p>Hobbies's sinceYear.</p>							|
| userId			| 			|  <p>Hobbies's userId.</p>							|

## Delete hobbies



	DELETE /hobbies/:id


## Retrieve hobbies



	GET /hobbies


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| q			| String			| **optional** <p>Query to search.</p>							|
| page			| Number			| **optional** <p>Page number.</p>							|
| limit			| Number			| **optional** <p>Amount of returned items.</p>							|
| sort			| String[]			| **optional** <p>Order of returned items.</p>							|
| fields			| String[]			| **optional** <p>Fields to be returned.</p>							|

## Update hobbies



	PUT /hobbies/:id


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| hobby			| 			|  <p>Hobbies's hobby.</p>							|
| passion			| 			|  <p>Hobbies's passion.</p>							|
| sinceYear			| 			|  <p>Hobbies's sinceYear.</p>							|
| userId			| 			|  <p>Hobbies's userId.</p>							|

# Users

## Create users



	POST /users


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Users's name.</p>							|

## Delete users



	DELETE /users/:id


## Retrieve users



	GET /users


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| q			| String			| **optional** <p>Query to search.</p>							|
| page			| Number			| **optional** <p>Page number.</p>							|
| limit			| Number			| **optional** <p>Amount of returned items.</p>							|
| sort			| String[]			| **optional** <p>Order of returned items.</p>							|
| fields			| String[]			| **optional** <p>Fields to be returned.</p>							|


