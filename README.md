# Bencode

Bencode is a pure-Python implementation of the original BitTorrent Bencode standard.

## Usage

    >>> import bencode
    >>> bencode.encode({'hello': ['world', 12]})
    'd5:hellol5:worldi12eee'
    >>> bencode.decode('d5:hellol5:worldi12eee')
    {'hello': ['world', 12]}
