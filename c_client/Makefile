# RelayRemote
# Shane Tully (shane@shanetully.com)
# shanetully.com
# https://github.com/shanet/RelayRemote
#
# Copyright (C) 2012 Shane Tully 
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU Lesser General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
# 
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU Lesser General Public License for more details.
# 
# You should have received a copy of the GNU Lesser General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.

VERSION = "\"1.0.0\""

all:
	gcc -std=c99 -O2 -Wall -Wextra -o c_client c_client.c -DVERSION=$(VERSION) -D_POSIX_C_SOURCE

clean:
	rm c_client
