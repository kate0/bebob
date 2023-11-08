# release-drafter-example

## Labels

The draft change note is constructed based on the available github labels:

### Change related labels

- bug - something isn't working
- internal - changes that do not relate to a bug or feature
- feature - new feature or improvement

### Semantic versioning labels

- GE - following change related to GE and should be included in GE changelog
- Maven - following change related to GE and should be included in Maven changelog
- Plugin - following change related to GE and should be included in Plugin changelog

### Other

- skip-log - Won't be included in the changelog

## Flow

- on push event work through the PR to check the labels with label_verifyer and add labels based on thema

