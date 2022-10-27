.content[]|select(.tailoredWords as $adj|all("small", "meme", "fluffy"; IN($adj[].word)))|.password
