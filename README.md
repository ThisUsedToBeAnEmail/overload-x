# NAME

overload::x - x on refs
========================
[![Build Status](https://travis-ci.org/ThisUsedToBeAnEmail/overload-x.png?branch=master)](https://travis-ci.org/ThisUsedToBeAnEmail/overload-x)
[![Coverage Status](https://coveralls.io/repos/ThisUsedToBeAnEmail/overload-x/badge.png?branch=master)](https://coveralls.io/r/ThisUsedToBeAnEmail/overload-x?branch=master)
[![CPAN version](https://badge.fury.io/pl/overload-x.svg)](https://metacpan.org/pod/overload-x)

# VERSION

Version 0.101

# SYNOPSIS

        use overlord::x qw/n/;

        my $arrayOfObjs = Obj->new x n(5)

        my ($one, $two, $three, $four) = @{ [qw/1 2 3/] x n(4) }

        ####

        my $arrayOfObjs = x(5, Obj->new)
        my ($one, $two, $three, $four) = x(4, [qw/1 2 3/])

## n

## x

# AUTHOR

LNATION, `<thisusedtobeanemail at gmail.com>`

# BUGS

Please report any bugs or feature requests to `bug-overload-x at rt.cpan.org`, or through
the web interface at [http://rt.cpan.org/NoAuth/ReportBug.html?Queue=overload-x](http://rt.cpan.org/NoAuth/ReportBug.html?Queue=overload-x).  I will be notified, and then you'll
automatically be notified of progress on your bug as I make changes.

# SUPPORT

You can find documentation for this module with the perldoc command.

        perldoc overload::x

You can also look for information at:

- RT: CPAN's request tracker (report bugs here)

    [http://rt.cpan.org/NoAuth/Bugs.html?Dist=overload-x](http://rt.cpan.org/NoAuth/Bugs.html?Dist=overload-x)

- AnnoCPAN: Annotated CPAN documentation

    [http://annocpan.org/dist/overload-x](http://annocpan.org/dist/overload-x)

- CPAN Ratings

    [http://cpanratings.perl.org/d/overload-x](http://cpanratings.perl.org/d/overload-x)

- Search CPAN

    [http://search.cpan.org/dist/overload-x/](http://search.cpan.org/dist/overload-x/)

# ACKNOWLEDGEMENTS

# LICENSE AND COPYRIGHT

Copyright 2018 LNATION.

This program is free software; you can redistribute it and/or modify it
under the terms of the the Artistic License (2.0). You may obtain a
copy of the full license at:

[http://www.perlfoundation.org/artistic\_license\_2\_0](http://www.perlfoundation.org/artistic_license_2_0)

Any use, modification, and distribution of the Standard or Modified
Versions is governed by this Artistic License. By using, modifying or
distributing the Package, you accept this license. Do not use, modify,
or distribute the Package, if you do not accept this license.

If your Modified Version has been derived from a Modified Version made
by someone other than you, you are nevertheless required to ensure that
your Modified Version complies with the requirements of this license.

This license does not grant you the right to use any trademark, service
mark, tradename, or logo of the Copyright Holder.

This license includes the non-exclusive, worldwide, free-of-charge
patent license to make, have made, use, offer to sell, sell, import and
otherwise transfer the Package with respect to any patent claims
licensable by the Copyright Holder that are necessarily infringed by the
Package. If you institute patent litigation (including a cross-claim or
counterclaim) against any party alleging that the Package constitutes
direct or contributory patent infringement, then this Artistic License
to you shall terminate on the date that such litigation is filed.

Disclaimer of Warranty: THE PACKAGE IS PROVIDED BY THE COPYRIGHT HOLDER
AND CONTRIBUTORS "AS IS' AND WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES.
THE IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE, OR NON-INFRINGEMENT ARE DISCLAIMED TO THE EXTENT PERMITTED BY
YOUR LOCAL LAW. UNLESS REQUIRED BY LAW, NO COPYRIGHT HOLDER OR
CONTRIBUTOR WILL BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, OR
CONSEQUENTIAL DAMAGES ARISING IN ANY WAY OUT OF THE USE OF THE PACKAGE,
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. 
