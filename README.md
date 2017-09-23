# Geometries

This is a repository of geometry files that my group and I use to test our PDE
solvers, mainly [pytential](https://github.com/inducer/pytential) and
[grudge](https://github.com/inducer/grudge).

Many of these geometries were created from scratch in the excellent
[FreeCad](https://www.freecadweb.org/) parametric CAD package.
Where available, I have included the source files so that variants
of the geometry can easily be created.

Once exported in [BRep format](https://www.opencascade.com/doc/occt-6.7.0/overview/html/occt_brep_format.html)
(which I recommend for more reliable operation than either STEP or IGES, at
least with OpenCASCADE-based software), these geometries are suitable for
mesh generation with [gmsh](http://gmsh.info/), from where our solvers
can read the mesh data using [meshmode](https://github.com/inducer/meshmode).

## License

(C)opyright Andreas Kloeckner 2017

This data is available under the [CreativeCommons Attribution 4.0 International
(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

You are free to:

*   Share -- copy and redistribute the material in any medium or format
*   Adapt -- remix, transform, and build upon the material
    for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

*   Attribution -- You must give appropriate credit, provide a link to the
    license, and indicate if changes were made. You may do so in any reasonable
    manner, but not in any way that suggests the licensor endorses you or your
    use.

*   No additional restrictions — You may not apply legal terms or technological
    measures that legally restrict others from doing anything the license
    permits.

Notices:

*   You do not have to comply with the license for elements of the material in
    the public domain or where your use is permitted by an applicable exception
    or limitation.

*   No warranties are given. The license may not give you all of the
    permissions necessary for your intended use. For example, other rights such
    as publicity, privacy, or moral rights may limit how you use the material.
