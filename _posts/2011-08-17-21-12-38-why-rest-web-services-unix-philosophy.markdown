### Why REST web services?

SOA embraces Unix.

The famous "Unix philosophy":

*Write <u>programs</u> that do one thing and do it well*

*Write <u>programs</u> to work together*

*Write <u>programs</u> that handle text streams, because that is a universal interface*

        # a sample pipelined shell command
        $ cat `find ~/bin/ -name "\*.sh"` | sed -e '/\^ \*#/d' | wc -l

replace "programs" with "services" => SOA
