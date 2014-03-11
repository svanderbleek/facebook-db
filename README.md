# Facebook DB

*Not The Dumbest Thing I've Ever Done*

Use a FB account for your database. I mean do it. This will let you
do it.

## Usage (do)

This really works. Look at the source for a thing that works. Also use this because you'll get your FB account taken away from you.

    client = FacebookDB::Client.new
    
    # Save something
    id = client.insert "Sup y'all"
    
    # Get something
    text = client.get id
    
    # Delete something
    client.delete id

That's all for now.
