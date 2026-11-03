# Kosher Filter site-list updates

Signed blocked-site lists for installed Kosher Filter programs. Installed filters download
`manifest.json`, `manifest.sig` and the listed files once a day and use them only if the signature
(made with a private key that is not here) and every file's SHA-256 match. Files are stored
byte-for-byte (`.gitattributes`: `* -text`); don't edit them by hand. Lists come from the
Block List Project (Unlicense) plus hand lists.
