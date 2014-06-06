Circuit_Diagram_Parser
======================

This code should take in a circuit diagram in image form(PNG, JPG, ...), identify components and topology, and print out the results as a netlist.

For example, the following diagram is getting turned into a netlist(Not in image form):

+--------+----------+----------+
|        |          |          |
V=10     R=1        L=1        C=1
|        |          |          |
+--------+----------+----------+
                    |
                  -----
                   ---
                    -
______________________________________
V N1 N0 dc 10
R N1 N0 1
L N1 N0 1
C N1 N0 1
