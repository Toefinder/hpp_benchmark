StatesPathFinder inStatePlanner is set to use the same path projector as the one selected with ProblemSolver. This makes it consistent with the settings in Manipulation-RRT.

The construction set benchmark is fixed to use M-RRT directly instead of helping it with producing a list of waypoints and connecting them using VisibilityPrm. This is because M-RRT is strong enough to run the benchmark on its own.
