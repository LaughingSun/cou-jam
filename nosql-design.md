=== user data

<user-key>        := <login> | <3rd-party-code> <3rd-party-id>

<login>           := 'email:' <email> | 'tel:' <intl-phone>

<3rd-party-code>  := <utc16-char>{2}

<3rd-party-id>    := <ascii-char>{128}

<user-id>         := 'uid:' <base64-digit>{32}

<user-record>     := <user-id> <user-nick> <cdate> <private-key>

<room-id>         := 'rid:' <base64-digit>{32}

<room-record>     := <room-id> <owner-uid> <room-name> <cdate>

<room-user-index> := <room-id> ( '+' <user-id ){0,}

