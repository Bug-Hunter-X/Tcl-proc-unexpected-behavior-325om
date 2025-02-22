This repository contains a simple Tcl script demonstrating a common error related to variable scoping within procedures. The bug.tcl file showcases the issue, while bugSolution.tcl provides a corrected version. The problem arises from how Tcl handles variable substitution within procedures. The solution clarifies the usage of local variables using the "upvar" command for proper scoping and referencing the correct values.