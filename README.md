# Skipblocks_COCO
Trying to build a classifier of a 5 class subset of the COCO dataset using a CNN with Skipblocks

## CNN with SkipBlocks

### Loss Graph comparison
<img src="images/69d6bcbc-a1c1-479e-92d3-84a8b6d76198.png" width="300" />

### Learning Rate 7e-4 CM
<img src="images/de35e674-f978-4715-aa42-6326c1ce5c06.png" width="300" />

### Learning Rate 5e-4 CM
<img src="images/e0d891ca-221c-4ca9-87f9-52b1fd46d360.png" width="300" />

## CNN without Skipblocks CM
<img src="images/bc6063cf-6389-4bde-b4be-545f00fdddd2.png" width="300" />

 Both of the two networks perform better than Network 3 without skipblocks which only achieved an accuracy of 46%. The network constructed with SkipBlocks not only is deeper and hence has potential to generalize more it also trains faster compared with Network 3. This is due to the skipblock mitigating the issue of vanishing gradient.
