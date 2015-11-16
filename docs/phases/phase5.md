### Phase 5: Styling and seeding and bonus (1 day)

## Rails
### Models
* Tag
* Comment

### Controllers
* Api::TagsController (create, destroy)
* Api::CommentsController (create, destroy, show)

### Views
* comments/show.json.jbuilder

## Flux
### Views (React Components)
* TagShow
* TagForm
* CommentShow
* CommentForm

### Stores
* Tag
* Comment

### Actions
* ApiActions.receiveAllTags
* ApiActions.receiveAllComments
* ApiActions.deleteTag
* ApiActions.deleteComment

### ApiUtil
* ApiUtil.fetchAllTags
* ApiUtil.createTag
* ApiUtil.destroyTag
* ApiUtil.fetchAllComments
* ApiUtil.createComment
* ApiUtil.destroyComment

## Gems/Libraries
