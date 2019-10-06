# hobbies API endpoints v0.0.1 - [Hobbies API server Here](https://user-hobby-api.herokuapp.com)



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
| hobby			| 			|  Hobbies's hobby.						|
| passion			| 			|  Hobbies's passion.							|
| sinceYear			| 			|  Hobbies's sinceYear.							|
| userId			| 			|  Hobbies's userId.							|

## Delete hobbies



	DELETE /hobbies/:id


## Retrieve hobbies



	GET /hobbies


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| q			| String			| **optional** Query to search.							|
| page			| Number			| **optional** Page number.							|
| limit			| Number			| **optional** Amount of returned items.							|
| sort			| String[]			| **optional** Order of returned items.							|
| fields			| String[]			| **optional** Fields to be returned.							|

## Update hobbies



	PUT /hobbies/:id


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| hobby			| 			|  Hobbies's hobby.						|
| passion			| 			|  Hobbies's passion.							|
| sinceYear			| 			|  Hobbies's sinceYear.							|
| userId			| 			|  Hobbies's userId.							|

# Users

## Create users



	POST /users


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  Users's name.							|

## Delete users



	DELETE /users/:id


## Retrieve users



	GET /users


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| q			| String			| **optional** Query to search.							|
| page			| Number			| **optional** Page number.							|
| limit			| Number			| **optional** Amount of returned items.							|
| sort			| String[]			| **optional** Order of returned items.							|
| fields			| String[]			| **optional** Fields to be returned.							|


