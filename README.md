<p align="center">
    <img style="border-radius: 100px" width="128" height="128" src="https://cdn.discordapp.com/avatars/417699816836169728/8ea8764772217e66ce7b7f9c3dd1561e.png?size=2048">
</p>

### Private Instagram API wrapper
- reverse engineered internal instagram api wrapper

# Features:
| Method        | return        | args             |
|---------------|---------------|------------------|
| [getPost](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs/getPost)        | [PostObject](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs#postobject)           | link             |
| [likePost](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs/likePost)      | [StatusObject](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs#statusobject)  | PostID           |
| [unlikePost](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs/unlikePost)    | [StatusObject](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs#statusobject)  | PostID           |
| addComment    | [CommentObject](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs#commentobject) | PostID, string   |
| deleteComment | [StatusObject](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs#statusobject)  | PostID,CommentID |
| [follow](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs/follow)        | [StatusObject](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs#statusobject)  | Username         |
| [unfollow](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs/unfollow)      | [StatusObject](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs#statusobject)  | Username         |
| [getUser](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs/getUser)          | [UserObject](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs#userobject)    | Username         |
| [search](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs/search)        | UserArray     | string           |

# [Docs](https://github.com/xNaCly/InstagramAPIwrapper/tree/master/docs)
