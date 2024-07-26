`contents/` contains a snapshot of the contents of the temp directory
https://github.com/bufbuild/buf/issues/3183 when the issue occurs.

My best guess is that the issue relates to the presence of both
`organization/api_platform/virtual_library/v1/operations/librarian/create_librarian_metadata__metadata.proto`
and
`organization/api_platform/virtual_library/v1/operations/librarian/create_librarian_metadata__metadata_other.proto`,
but I'm not sure.
