●Tell me how to remove them locally and remotely.

Delete Locally:
git branch -d dev
git branch -d test

Delete Remotely:
git push origin --delete dev
git push origin --delete test

●Tell me how to list tags.
git tag

●Tell me how to delete tag locally and remotely.

To delete remote tag
git push origin --delete v1.7

To delete local tags
git tag -d v1.7
