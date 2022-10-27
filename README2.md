.content[]
    | select(
        .tailoredWords as $adj
        | all("small"; IN($adj[].word))
    )
    | .password
