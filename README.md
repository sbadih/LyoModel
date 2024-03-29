# LyoModel
This page provides a python implementation of the Tchessalov model used to calculate the evolution of the state of a product during a lyophilization cycle as a function of operating conditions(shelf temperature,chamber pressure). Follow the Guideline for Lyophilization Model document to implement the model.

The Tchessalov model is a mathematical model based on the energy balance of the frozen product and the mass balance of the water vapor in the dried product. The main parameters of the model are Kv (heat transfer coefficient) and Rp (resistance of dried layer to vapor flow). Given a set of operating conditions(shelf temperature,chamber pressure), the model will output the drying time and the product temperature. This model can be used to build a design space for freeze drying of a formulation of interest, providing a robust method of finding optimal operating conditions that reduce drying time while ensuring product quality is maintained(product temperature doesn't go beyond the collapse temperature). More details on the Tchessalov model can be found in the article cited below:

Giordano A, Barresi AA, Fissore D. On the use of mathematical models to build the design space for the primary drying phase of a pharmaceutical lyophilization process. J Pharm Sci. 2011 Jan;100(1):311-24. doi: 10.1002/jps.22264. Epub 2010 Jun 23. PMID: 20575053.

