WTF Did I Do Yesterday?
=======================

Maybe it's an age thing, but I find it really difficult to remember what it was I did yesterday when it comes to the morning scrum. `wtfdidy` is a command line tool written in Ruby, a bit like a todo app, but in reverse.

You can use it to log the things you do during the day and then tomorrow, 5 minutes before your stand-up, when you're desperately trying to remember WTF you did yesterday, you can type `wtfdidy` and get a nice list of what it was you did.

### Installation

Clone the repo, copy the tool to your PATH and change the permissions to make it executable - `chmod a+x wtfdidy`.

### Usage

To add an item to the list simply type the thing you did after the command, you don't even need to use quotes (in most cases):

    wtfdidy I wrote this really useful thing to remind me WTF I did yesterday

To retrieve a list of things you did yesterday, just type the command without arguments

    wtfdidy
