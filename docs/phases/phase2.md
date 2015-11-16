### Phase 2: Flux Architecture and Album/Photo CRUD (3 days)

## Rails
### Models

### Controllers

### Views

## Flux
### Views (React Components)
* AlbumForm
* AlbumIndex
  - AlbumIndexItem
* Album
* Thumbnail
* Photo

### Stores
* Album
* Photo

### Actions
* ApiActions.receiveAllAlbums
* ApiActions.receiveSingleAlbum
* ApiActions.receiveAllThumbnails
* ApiActions.receiveSinglePhoto
* ApiActions.deleteAlbum
* ApiActions.deletePhoto

### ApiUtil
* ApiUtil.fetchAllAlbums
* ApiUtil.fetchSingleAlbum
* ApiUtil.createAlbum
* ApiUtil.editAlbum
* ApiUtil.destroyAlbum
* ApiUtil.fetchAllThumbnails
* ApiUtil.fetchSinglePhoto
* ApiUtil.editPhoto
* ApiUtil.destroyPhoto

## Gems/Libraries
* Flux Dispatcher
* Twitter Bootstrap
