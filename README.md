# Udacity-Python-Introduction

The project involved creating a graph data structure to capture the network of a group of friends.

1) create_data_structure - The first step was to create a data structure to store all information about a person like the friends one has and the games one likes.
                           The data structure chosen is a dictionary where the keys represent a user and 
                           the value is another dictionary with keys - connected and games liked with values being the list of friends and list of games like respectively.

2) get_connections - Returns the friends for a user.

3) get_games_liked - Returns the games a user likes

4) add_connection - Adds a connection between two second user and first user.

5) add_new_user - To add a new user to the network

6) get_secondary_connections - The link between friends of friends is taken to show who are connected to whom and through which user.

7) count_common_connections - Counts the common connections between two users.

8) find_path_to_friend - To find through what connections a user is connected to another user

9) MYOP - Make your own function was a creative part of the assignment where any function could be created to perform any operation. 
          The MYOP implemented here is a basic recommender system where people directly connected to each other(friends) are recommended games that their friend likes
