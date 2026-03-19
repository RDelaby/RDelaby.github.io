The data is subsequent triples of involutions r1,r2,r3 in a list followed by their associated diagram in increasing size of the residues order. 
Once all the geometries have been enumerated, the algorithm gives the number of the geometries and a list of l such that 
l[i][1] is a residue size for a geometry and l[i][2] is the number of geometries having l[i][1] as residue size.
Annotated example for G = PGL(2,27). The commentaries are after // which do not appear in the original txt file.

// first triple of involutions.
[ 
    (1, 5)(2, 25)(3, 26)(4, 11)(6, 15)(7, 18)(8, 16)(10, 21)(12, 20)(13, 22)(14,
        28)(17, 24)(23, 27),
    (1, 14)(2, 25)(3, 27)(4, 17)(5, 6)(7, 28)(8, 20)(9, 23)(10, 26)(11, 18)(12,
        13)(15, 19)(16, 21),
    (1, 17)(2, 24)(3, 25)(4, 28)(5, 12)(7, 8)(9, 18)(10, 26)(11, 13)(14, 16)(15,
        22)(19, 20)(23, 27)
]
// diagram for the first list of involutions.
{1, 2} [ 13, 13, 13 ]
{1, 3} [ 13, 13, 13 ]
{2, 3} [ 13, 13, 13 ]
// second list of involutions.
[
    (1, 14)(2, 15)(3, 6)(4, 20)(7, 18)(8, 22)(9, 26)(10, 13)(12, 24)(16, 23)(17,
        25)(19, 27)(21, 28),
    (2, 18)(3, 19)(4, 17)(5, 23)(6, 11)(7, 8)(9, 28)(10, 15)(12, 21)(13, 14)(16,
        26)(22, 25)(24, 27),
    (1, 19)(2, 20)(3, 22)(4, 11)(5, 7)(6, 26)(9, 12)(10, 17)(14, 16)(15, 23)(18,
        27)(21, 25)(24, 28)
]
// diagram for the second list of involutions.
{1, 2} [ 14, 14, 14 ]
{1, 3} [ 14, 14, 14 ]
{2, 3} [ 14, 14, 14 ]
// number of geometries is 2.
2
// There is 1 geometry with residues of size 13 and 1 geometry with residues of size 14.
[
    [ 13, 1 ],
    [ 14, 1 ]
]
// Computation time is 0.830 seconds.
0.830
