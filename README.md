# data

This repo is for medium-sized data to 'play' with (i.e. develop with)

## Aim for files to be <10 MB each and make 9-10 files per dataset

- This allows us to have 10 datasets per repo

## How we rationalized to reach the above aim

- Without warnings, you can push 20 <50 MB files = 1 GB of data
- With warnings, you can push 10 <100 MB files = 1 GB of data

- Google says we are allowed 75 GB per account (I'm not sure if this is true)
  - This would mean a max of 75 x 1GB repos
  - This is good reason to number our data repos, so we can keep track of multiples 

- It is nice to have multiple files of the same type to loop through when developing pipelines
- The minium # of files you can loop over is 2
- In biology, 9 samples can give you an informative insight into the diversity of your samples (no guarantees here!)
- The maximum amount of data that a repo can hold is 1 GB
- It would be nice to **not** have to make a whole new repo for every play dataset we generate


Aim to keep files <10 MB
- this allows us to upload 10 files per dataset and 10 datasets per data repo


Fastq files can be multiple GB, so we won't be able to use this system for those. But we can use this system to exchange medium-sized files.


