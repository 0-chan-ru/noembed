# Noembed — oEmbed everything.

## Requirements

- Perl 5 (5.32.0)
- cpanminus

## Installation

`cpanm --installdeps .`

Maybe require manual install (other) deps:  
`cpan install`  
`yes`  
and/or  
`cpan install WWW::Form::UrlEncoded Params::Util String::CRC32 module HTML::Entities Net::SSLeay module LWP::Protocol::https::Socket`

If there are errors `Can't locate object method "new" via package...` anyway then clear install perl (force remove all version and reinstall perl).




## Run as Perl PSGI service

`plackup -Ilib bin/noembed.psgi`
