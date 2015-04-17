# NAME

App::PAUSE::TimeMachine - Web server and CLI to display PAUSE package list in previous time

# SYNOPSIS

For `pausetm` command line usage, see [pausetm](https://metacpan.org/pod/pausetm).

App::PAUSE::TimeMachine provides a PSGI web application coderef, which
you can use in your own application or apply whatever middleware you'd
like to apply.

    my $app = App::PAUSE::TimeMachine->new->psgi_app;

# AUTHOR

Tatsuhiko Miyagawa <miyagawa@bulknews.net>

# COPYRIGHT

Copyright 2015- Tatsuhiko Miyagawa

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[pausetm](https://metacpan.org/pod/pausetm)
