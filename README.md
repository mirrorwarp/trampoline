# trampoline

Purpose-built proxy and cache for the Scratch API. It is used by [forkphorus](https://forkphorus.github.io) and [MirrorWarp](https://mirrorwarp.github.io). It only implements a few routes that these sites need -- it is not a general-purpose proxy. There is no guarantee of compatibility. It uses very heavy caching to reduce the amount of requests sent to the upstream Scratch API.

The app assumes it's behind a reverse proxy such as nginx.

An instance of this service is hosted at https://trampoline.mirrorwarp.github.io/
