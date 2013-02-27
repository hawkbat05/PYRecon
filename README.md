PYRecon v0.1 - Copyright 2013 James Slaughter,
This file is part of Recon v0.1.

PYRecon v0.1 is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

PYRecon v0.1 is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with PYRecon v0.1.  If not, see <http://www.gnu.org/licenses/>.

Usage: [required] --mode [optional] --target --supresswget --supressemail --debug --help
       Required Arguments:
       --mode [auto, manual, fail2ban] - auto to be run as a scripted cron job, manual to be run as a one off and fail2ban to be run with Fail2ban
       Optional Arguments:
       --target[Must be IP to work properly]
       --supresswget - will not attempt a WGET against the target.
       --supressemail - will not send out an e-mail summarizing the actions taken.
       --debug - prints verbose logging to the screen to troubleshoot issues with a recon installation.
       --help - You're looking at it!
