# Open source platform for analysing and sharing worm behaviour data.

Recording, analysing, and sharing behaviour data can be challenging.  The open source tools linked here are designed to help.

## [Tierpsy Tracker](http://ver228.github.io/tierpsy-tracker/)
[Tierpsy Tracker](http://ver228.github.io/tierpsy-tracker/) uses high resolution videos to track multiple animals at a time, but can also extract detailed postural features that are normally associated with motorised "single-worm" trackers with smaller fields of view.  Tierspy therefore provides the throughput of multi-worm tracking with the phenotypic richness of single-worm tracking.  Segmented videos, tracking results, and feature files are saved using the open source hierarchical data format (HDF5) that provides lossless compression and intuitive organisation of data and metadata. We have also developed an HDF5 video player with adjustable speed (including frame-by-frame advancing) and zoom, which is especially important for high resolution multi-worm tracking data.  The viewer allows manual review of segmentation accuracy by toggling worm outline and skeleton overlays during playback.


## [Searchable behaviour database](http://movement.openworm.org/)
There are two main practical challenges with behaviour data: videos are large and it is difficult to find what you're looking for.  We have created a Community at Zenodo for sharing worm data that generates DOIs, making the data citable.  The data are stored in a relatively raw form for reanalysis as well as more processed feature time series and phenotypic fingerprints.  A [database and frontend](http://movement.openworm.org/) developed in collaboration with OpenWorm make the data searchable so that you can find data not only based on genetics or metadata, but based on the behaviour itself.  An intuitive interface makes exploring behavioural data faster and easier than before.


## [Worm tracker Commons Object Notation (WCON)](https://github.com/openworm/tracker-commons)
Many behavioural experiments depend on the details and so many groups still develop their own analysis tools.  However, the intermediate output of these analyses is often relatively similar.  Therefore, a significant part of the barrier to sharing is not fundamental, but a simple result of a lack of coordination.  [WCON](https://github.com/openworm/tracker-commons) is a file format that provides a simple way to share worm tracking data between labs and analysis packages. It supports single and multi-worm tracking with high and low resolution, the inclusion of critical metadata, and a flexible facility for adding group-specific custom features.  Because WCON is a subset of the widely supported [JSON](http://json.org/) format, it is both human and machine readable. Open source WCON readers are available for Python, MATLAB, Scala, and R.



