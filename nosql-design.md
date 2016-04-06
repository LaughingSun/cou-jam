=== user data

<user-key>        := 'login=' ( <login> | <3rd-party-code> <3rd-party-id> )

<3rd-party-code>  := <unicode-char>{2}

<3rd-party-id>    := <ascii-char>{128}

<login>           := <email> | <intl-phone>

<user-id>         := <base64-digit>{32}

<user-record>     := <user-id> <user-nick> <cdate> <pepper>
