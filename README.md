# SwarmOS dogfood

A private staging repository for a native Codex WorkUnit. The first task adds
`hello.txt` containing `hello from SwarmOS` followed by a newline.

The workflow uses native isolation, a human plan gate, and protected policy files.
Run `codex login status` and `swarm doctor` on a qualified Linux worker before
starting. Test publication uses GitHub credentials restricted to this repository.
