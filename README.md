Code foundations Refactoring discussion exercise:

Scenario:

    You have just been assigned to continue developing a Yatzy app.
    The previous consultant hastily left the project and now you have to
    continue the development.
    Fortunately the consultant wrote unit test for the existing functions.
    The program currently supports scoring of Fours, Fives and Sixes and Pair
    and Three of a kind.

    In the upcoming Sprint the Product Owner wants you to implement the scoring
    function for Four of a kind as well as Ones, Twos and Threes.


    Scoring rules:

        Ones, Twos, Threes, Fours, Fives, Sixes:

            The player scores the sum of the dice that reads one, two, three,
             four, five or six, respectively. For example:

            1,1,2,4,4 placed on "fours" scores 8 (4+4)
            2,3,2,5,1 placed on "twos" scores 4 (2+2)
            3,3,3,4,5 placed on "ones" scores 0

        Four of a kind:

            If there are four dice with the same number, the player scores the
             sum of these dice. For example, when placed on "four of a kind":

            2,2,2,2,5 scores 8 (2+2+2+2)
            2,2,2,5,5 scores 0
            2,2,2,2,2 scores 8 (2+2+2+2)