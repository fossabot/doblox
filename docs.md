## Classes

<dl>
<dt><a href="#RobloxUser">RobloxUser</a></dt>
<dd></dd>
<dt><a href="#Client">Client</a></dt>
<dd></dd>
</dl>

## Typedefs

<dl>
<dt><a href="#UserResolvable">UserResolvable</a> : <code><a href="#RobloxUser">RobloxUser</a></code> | <code>discord.UserResolvable</code></dt>
<dd><p>A value that resolves to a discord user or roblox user</p>
</dd>
</dl>

<a name="RobloxUser"></a>

## RobloxUser
**Kind**: global class  

* [RobloxUser](#RobloxUser)
    * [new RobloxUser(data, partial)](#new_RobloxUser_new)
    * [.username](#RobloxUser+username) : <code>String</code>
    * [.id](#RobloxUser+id) : <code>Number</code>
    * [.description](#RobloxUser+description) : <code>String</code>
    * [.createdAt](#RobloxUser+createdAt) : <code>Date</code>
    * [.partial](#RobloxUser+partial) : <code>Boolean</code>

<a name="new_RobloxUser_new"></a>

### new RobloxUser(data, partial)

| Param | Type | Description |
| --- | --- | --- |
| data | <code>Object</code> | RobloxUser data |
| partial | <code>Boolean</code> | Whether its a partial |

<a name="RobloxUser+username"></a>

### robloxUser.username : <code>String</code>
Username of the user

**Kind**: instance property of [<code>RobloxUser</code>](#RobloxUser)  
<a name="RobloxUser+id"></a>

### robloxUser.id : <code>Number</code>
ID of the user

**Kind**: instance property of [<code>RobloxUser</code>](#RobloxUser)  
<a name="RobloxUser+description"></a>

### robloxUser.description : <code>String</code>
Description of the user

**Kind**: instance property of [<code>RobloxUser</code>](#RobloxUser)  
<a name="RobloxUser+createdAt"></a>

### robloxUser.createdAt : <code>Date</code>
Date at which the user was created at

**Kind**: instance property of [<code>RobloxUser</code>](#RobloxUser)  
<a name="RobloxUser+partial"></a>

### robloxUser.partial : <code>Boolean</code>
Whether the data is partial

**Kind**: instance property of [<code>RobloxUser</code>](#RobloxUser)  
<a name="Client"></a>

## Client
**Kind**: global class  

* [Client](#Client)
    * [new Client(noblox, client)](#new_Client_new)
    * [.getRobloxUser(user)](#Client+getRobloxUser)

<a name="new_Client_new"></a>

### new Client(noblox, client)

| Param | Type | Description |
| --- | --- | --- |
| noblox | <code>noblox</code> | Your noblox module object, not required but kept for backwards compatibility. |
| client | <code>discord.Client</code> | A discord client |

<a name="Client+getRobloxUser"></a>

### client.getRobloxUser(user)
**Kind**: instance method of [<code>Client</code>](#Client)  

| Param | Type | Description |
| --- | --- | --- |
| user | <code>discord.UserResolvable</code> | The discord user to get robloxUser of |

<a name="UserResolvable"></a>

## UserResolvable : [<code>RobloxUser</code>](#RobloxUser) \| <code>discord.UserResolvable</code>
A value that resolves to a discord user or roblox user

**Kind**: global typedef  
