# ExploreUK finding aid metadata samples

This is a collection of test data for people at the 
[University of Kentucky Libraries](https://libraries.uky.edu) (UKL)
who need a sample of finding aid metadata from
[ExploreUK](https://exploreuk.uky.edu).

## What will you find here?

```bash
└── samples
    └── xt7jws8hf793
        ├── 97ms501.dao.xml
        ├── 97ms501.xml
        └── mets.xml
```

There are 20 finding aids represented in this sample. 19 were selected randomly, and
one was deliberately selected because it was the largest collection in ExploreUK at
the time of selection.

Each sample directory is named by the [ARK identifier](https://arks.org/about/) for the
corresponding collection. At the time of writing, the associated collection on ExploreUK
consists of the prefix `https://exploreuk.uky.edu/catalog/` followed by the Assigned Name,
for example: https://exploreuk.uky.edu/catalog/xt7jws8hf793 .

Within each sample directory there will be one [METS](https://www.loc.gov/standards/mets/) file,
named `mets.xml`. In the `fileSec` for this METS file there is a `fileGrp` with `ID="FileGrpFindingAid"`.
The files referenced in this `fileGrp` are [EAD](https://loc.gov/ead/) files which should also
appear in the sample directory.

## Restrictions on use

This package is primarily intended for use by UKL employees. The metadata
within was produced by UKL employees and was published by us on ExploreUK.
We offer access to our metadata published on ExploreUK to interested harvesters for their
own information-seeking purposes. The physical rights to the materials in
the collections described within are generally held by the
[Special Collections Research Center](https://libraries.uky.edu/locations/special-collections-research-center)
at the University of Kentucky Libraries.

## Who built this

This data sample was originally selected and collected by MLE Slone on 2024-03-22.
