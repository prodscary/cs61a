This file holds the tests that you create. Remember to import the python file(s)
you wish to test, along with any other modules you may need.
Run your tests with "python3 ok -t --suite SUITE_NAME --case CASE_NAME -v"
--------------------------------------------------------------------------------

Suite 1


    

    Case Example
        >>> import ants, importlib, ants_gui, graphics, state, ucb, utils
        >>> importlib.reload(ants)
        >>> hive = ants.Hive(ants.AssaultPlan())
        >>> dimensions = (2, 9)
        >>> colony = ants.AntColony(None, hive, ants.ant_types(),
        >>> ants.dry_layout, dimensions)
        >>> ants.bees_win = lambda: None
        >>> # QueenAnt Placement
        >>> queen = ants.QueenAnt()
        >>> impostor = ants.QueenAnt()
        >>> print(queen.queenList)
        [True]
