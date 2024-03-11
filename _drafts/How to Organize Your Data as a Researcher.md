---
layout: post
blurb: Can you tell my thesis is due soon? 
---

## Context
I'm currently writing a thesis about a laser rangefinding system for gathering
fish length data. Here are some different ways that can change: 
- Every single device has different camera parameters
- Every single trial run has different laser parameters
- Different calibration procedures may generate different parameters
- We get data from different experiments

Since there are so many things that can vary and that I may want to include in
the manuscript, I need a good way to organize my data.
    
## My Current System
My current system goes a little something like this.
    
### Numbered Trial Folders
Every new experiment has a new folder. Currently these are just numbered. Each
of these contains a README explaining what data I'm using and why.

## Focus on Reproducibility, Not Efficiency
I know it might be tempting to keep everything in one place and reference
particular files or folders using relative paths. Don't do this unless you know
that your file structure is guaranteed to not change, or maybe if you're using
some kind of database. For me, the amount data I'm working with for each
experiment is relatively low (a few csv files), so I'm OK with having multiple
copies of the same file in different trial directories.

## Keep Trials Separate

## Know the 5 W's
