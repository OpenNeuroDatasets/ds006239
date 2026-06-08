# Known Issues

1) Anatomical images in versions prior to v1.0.6 had a defacing issue. Users should use v1.0.6 or later for any analyses involving anatomical images. Functional data and associated behavioral files are not affected by this issue.

2) In all the events TSV files, trials with no response are coded as 'n/a'. For analysis purposes, no-response trials are suggested to be treated as incorrect '0' as failure to perform the task. Note: In the data-sharing paper (Wang et al., 2025), summary accuracy statistics excluded no-response trials; however, for any inferential analyses, users are advised to treat no-response trials as incorrect.