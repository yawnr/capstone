# FollowFocus

[FollowFocus][followfocus]

[followfocus]: http://www.followfocus.co

## Minimum Viable Product

FollowFocus is photography application inspired by Flickr built using
Ruby on Rails and React.js. FollowFocus allows users to:

- [ ] Create an account
- [ ] Log in / Log out
- [ ] Create albums
- [ ] Upload photos to albums
- [ ] Add tags to photos
- [ ] Search for photos by tags or usernames
- [ ] View a randomized homepage photo gallery

## Design Docs
* [View Wireframes][view]
* [DB schema][schema]

[view]: ./docs/views.md
[schema]: ./docs/schema.md

## Implementation Timeline

### Phase 1: User Authentication, Album and Photo Models and JSON API (1 day)

- Splash page with sign up / sign in dialogue
- User authentication with BCrypt
- JSON API for albums, photos, and thumbnails

[Details][phase-one]

### Phase 2: Flux Architecture and Album/Photo CRUD (3 days)

- Flux architecture
- Album and Photo stores with corresponding CRUD actions
- React views for: `AlbumForm`, `AlbumIndex`, `AlbumIndexItem`, `Album`, `Thumbnail`, and `Photo`.
- At the end of Phase 2, Albums can be created, viewed, edited, and destroyed in the browser.
- Basic CSS styling

[Details][phase-two]

### Phase 3: Nav bar and uploader (2 days)

- Navigation bar component
- Uploader with ability to upload multiple photos simultaneously and
  add to existing or new album
- Drag and drop upload functionality using Jquery File Upload

[Details][phase-three]

### Phase 4: Homepage Gallery (1 day)

- Homepage gallery with randomized photos that when clicked on, navigate to
  the containing album

[Details][phase-four]

### Phase 5: Styling and seeding (1 day)

- Styling and transitions
- Seed db with dummy user accounts/albums/photos

### Bonus Features (TBD)
- [ ] Private albums
- [ ] Tag and user subscriptions that feed into homepage gallery
- [ ] Fixed height scrollable gallery with opacity and size transitions (see wireframe)
- [ ] Likes and comments on photos
- [ ] Multiple sessions

[phase-one]: ./docs/phases/phase1.md
[phase-two]: ./docs/phases/phase2.md
[phase-three]: ./docs/phases/phase3.md
[phase-four]: ./docs/phases/phase4.md
