# libgdx-distancefieldgen
A standalone version of gdx-tools' DistanceFieldGenerator.

See the Releases section for runnable JARs.

[See the libGDX wiki for more information](https://libgdx.com/wiki/graphics/2d/fonts/distance-field-fonts).

You can run the JAR with a command like the following, changing downscale and spread as the wiki describes:
```
java -jar DistanceFieldGen-1.11.0.0.jar input.png output.png --downscale 8 --spread 64
```

This was taken from inside [libGDX](https://github.com/libgdx/libgdx) and moved so it can be run more easily from
outside that framework. It still has the same license as libGDX.
