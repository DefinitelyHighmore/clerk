# clerk
A Ticketing System for collaboration between multiple players

## Download
Get the latest release from releases!

## Usage
* Type the following command to get a Ticket Manager:

```mcfunction
function clerk:manager
```

* That's it! The system explains itself quite well, and most things have hoverEvent descriptions for what they do.
* Multiple people can undertake a single ticket
* Tickets you assign to yourself are available in the ``[Assigned Tickets]`` menu.
* More options are available when you expand a ticket, including teleporting to the ticket's creation location, assining/unassigning a ticket to yourself, resolving a ticket and deleting a ticket.

# Removing
* After you are done with ticketing (and your project is complete), you can remove the datapack and run the following command to delete it's storage:

```mcfunction
data removte storage clerk:internal root
```
