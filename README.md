# integration
Sample code to support integration of remove.bg's AI background removal
$ unzip no-bg.zip                      && \
  convert color.jpg alpha.png             \
    -compose CopyOpacity                  \
    -composite no-bg.png
