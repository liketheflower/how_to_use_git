# how_to_use_git


# big file: install lfs  

https://github.com/git-lfs/git-lfs

# big file

error: failed to push some refs to 'https://github.com/liketheflower/SUNRGBtoolbox.git'
owners-MacBook-Pro:SUNRGBtoolbox jimmy$ git lfs ls-files
owners-MacBook-Pro:SUNRGBtoolbox jimmy$ git lfs migrate import --include="*.mat"
migrate: Fetching remote refs: ..., done                                                                                       
migrate: Sorting commits: ..., done                                                                                            
migrate: Rewriting commits: 100% (1/1), done                                                                                   
  master	653deb379558bc30a2dc6c33e42ce236506a5379 -> 3c649ed38919f813f327ee3f91c06bc6f7270917
migrate: Updating refs: ..., done                                                                                              
migrate: checkout: ..., done                                                                                                   
owners-MacBook-Pro:SUNRGBtoolbox jimmy$ git lfs ls-files
3a1c771063 - Metadata/SUNRGBD2Dseg.mat
57410ead85 - Metadata/SUNRGBDMeta.mat
830a9bd385 - Metadata/dection19list.mat
4b3a8cd065 - Metadata/groundtruth.mat
04d094cb35 - Metadata/seg37list.mat
d12ec803ce - Metadata/seglistall.mat
owners-MacBook-Pro:SUNRGBtoolbox jimmy$ git push origin master
Uploading LFS objects:  83% (5/6), 966 MB | 2.3 MB/s     
