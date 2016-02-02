# Parse Client Library

A parser combinator library dedicated to the Thicket language.

## Modules compilation

```sh
> thicket compile -i <..>/thicket-library-core/bin -p Core -o obj -v `find src/main/thicket -name \*.tkt`
...
```

## Package construction

```sh
> thicket package -i obj/ -o bin/ -i src/main/js/ -v -s -n parser.pkt 
...
```

## License

Copyright (C)2015 D. Plaindoux.

This program is  free software; you can redistribute  it and/or modify
it  under the  terms  of  the GNU  Lesser  General  Public License  as
published by  the Free Software  Foundation; either version 2,  or (at
your option) any later version.

This program  is distributed in the  hope that it will  be useful, but
WITHOUT   ANY  WARRANTY;   without  even   the  implied   warranty  of
MERCHANTABILITY  or FITNESS  FOR  A PARTICULAR  PURPOSE.  See the  GNU
Lesser General Public License for more details.

You  should have  received a  copy of  the GNU  Lesser General  Public
License along with  this program; see the file COPYING.  If not, write
to the  Free Software Foundation,  675 Mass Ave, Cambridge,  MA 02139,
USA.

