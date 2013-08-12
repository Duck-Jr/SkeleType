SkeleType
=========

Are you frustrated that the font of your choice doesn't have all the 
characters? Does your screen fill with &#xFFFD;&#xFFFD;&#xFFFD; when 
all you're trying to do is read and write in Chinese? Is Windows 
making you use MS Mincho just to do these things?

Well, hi there! Billy Mays here, presenting to you the open-source 
SkeleType system!

Jokes aside, SkeleType is a system through which character rendering 
engines can dynamically generate characters missing from fonts, 
based on what characters already in the font look like. It provides 
descriptions of the strokes required to draw every character in the 
Universal Character Set.

SkeleType only contains information about the shapes that make up 
characters. It does not specify how to render them; some research 
and development may be required for us to reach that step. We 
encourage you to develop character drawing routines for SkeleType,
whether they be open-source or not.

### License Information

SkeleType is free software: you can redistribute it and/or modify
it under the terms of the [GNU General Public License] 
(http://www.gnu.org/licenses/gpl-3.0.html) as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

SkeleType is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with SkeleType.  If not, see <http://www.gnu.org/licenses/>.

We will be thrilled to license the right to make proprietary 
software from SkeleType on a reasonable and non-discriminatory basis 
as soon as we have the necessary resources.
