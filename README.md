Repro Steps

1) Run install
2) Run `nx run app-a-e2e:e2e:production`
3) "Required property '__unparsed__' is missing"

Files of note:
`apps/app-a-e2e/project.json` => `serve-for-e2e` target
