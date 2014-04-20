# Generic Tree XML schema

## Rationale

The Generic Tree XML schema can be used to add a hierarchical structure to
arbitrary XML based information.

The GenericTree XML schema: [`gtr.xsd`](gtr.xsd).

A restriction of the GenericTree XML schema that allows only Dublin Core
elements inside the content element: [`gtr_dc.xsd`](gtr_dc.xsd).

The schema used to define the Dublin Core elements used in `gtr_dc.xsd` can be
found [here](http://dublincore.org/schemas/xmls/simpledc20021212.xsd).

An example instance for `gtr_dc.xsd`:
[`gtr_dc_example.xml`](gtr_dc_example.xml).

## TODO

* More introductory information.

* Simple example without extra Dublin Core schema.

## License

Copyright 2014 Martin Hoppenheit <martin@hoppenheit.info>

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more
details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <http://www.gnu.org/licenses/>.
