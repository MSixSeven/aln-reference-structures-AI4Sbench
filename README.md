# AlN reference structures

Reference answer structures for the AlN atomistic structure benchmark.

All 10 POSCAR files retain their original filenames and bytes. The manifest records source-relative paths, species counts and SHA-256 checksums.

| Case | File | Al | N |
|---|---|---|---|
| step_y | [AlN_psf_Ystep-20y.vasp](AlN_psf_Ystep-20y.vasp) | 880 | 880 |
| step_z | [AlN_psf_Zstep-20z.vasp](AlN_psf_Zstep-20z.vasp) | 880 | 880 |
| a1 | [AlN-a1-ortho-large.vasp](AlN-a1-ortho-large.vasp) | 828 | 828 |
| a2 | [AlN-a2-ortho-large.vasp](AlN-a2-ortho-large.vasp) | 744 | 744 |
| a3 | [AlN-a3-ortho-large.vasp](AlN-a3-ortho-large.vasp) | 788 | 788 |
| b1 | [AlN-b1-ortho-large.vasp](AlN-b1-ortho-large.vasp) | 696 | 696 |
| b2 | [AlN-b2-ortho-large.vasp](AlN-b2-ortho-large.vasp) | 732 | 732 |
| b3 | [AlN-b3-ortho-large.vasp](AlN-b3-ortho-large.vasp) | 656 | 656 |
| hexagonal | [AlN-hexagonal-ortho.vasp](AlN-hexagonal-ortho.vasp) | 2964 | 2964 |
| mixed_ac | [AlN_a+c_dislocation.vasp](AlN_a+c_dislocation.vasp) | 11484 | 11484 |

These ten final structures comprise two PSF steps, six corners, one hexagonal domain and one mixed a+c dislocation. They are assessment references and must be excluded from solver inputs during a controlled evaluation. They do not define complete migration trajectories.

The Z-step file preserves an original comment containing 10z; its cell and coordinates correspond to 20c.

A calibrated automatic grader and a complete independent construction workflow remain to be completed.

## License

A data reuse license has not yet been specified by the contributor.
