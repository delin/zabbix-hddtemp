# zabbix-hddtemp

Disk temperature template for Zabbix via hddtemp

# License

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

# Installation
1. Install hddtemp utility (apt-get install hddtemp)
2. Make sure hddtemp is running as daemon on localhost:7634 (`nc localhost 7634`)
3. Copy hddtemp.conf to /etc/zabbix/zabbix_agentd.conf.d/
4. Import zbx_hddtemp.xml in Zabbix templates


Tnx @vovka1200
