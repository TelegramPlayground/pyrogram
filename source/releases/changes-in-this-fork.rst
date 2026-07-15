UNRELEASED VERSION
==================


Scheme layer used: 227
---------

- Allow to set emoji status for channel.
- View `new and changed <https://telegramplayground.github.io/TG-APIs/TL/diff/tdlib.html?from=225&to=227>`__ `raw API methods <https://telegramplayground.github.io/TG-APIs/TL/diff/tdesktop.html?from=225&to=227>`__.

Scheme layer used: 225
---------

- Added ``members_only`` and ``country_codes`` to :meth:`~pyrogram.Client.send_poll`, :meth:`~pyrogram.types.Message.reply_poll` and :obj:`~pyrogram.types.Poll`.
- Added the :obj:`~pyrogram.filters.guest_message_query_id`.
- Added the classes :obj:`~pyrogram.types.SentGuestMessage` and :obj:`~pyrogram.types.BotAccessSettings`.
- Added the methods :meth:`~pyrogram.Client.answer_guest_query`, :meth:`~pyrogram.types.Message.answer`, :meth:`~pyrogram.Client.delete_message_reaction`, :meth:`~pyrogram.Client.delete_all_message_reactions`, :meth:`~pyrogram.Client.get_user_personal_chat_messages` and :meth:`~pyrogram.Client.get_user_personal_chat_messages_count`.
- Added the fields ``guest_bot_caller_user``, ``guest_bot_caller_chat``, ``guest_query_id``, ``summary_language_code``, ``is_paid_star_suggested_post``, ``is_paid_ton_suggested_post``, ``schedule_repeat_period``, ``restriction_reason`` to the :obj:`~pyrogram.types.Message`.
- Added the parameter ``return_bots`` to the method :meth:`~pyrogram.Client.get_chat_administrators`.
- Added the field ``supports_guest_queries`` to the :obj:`~pyrogram.types.User`.
- Added ``description_media`` and ``explanation_media`` in :meth:`~pyrogram.Client.send_poll` and :meth:`~pyrogram.types.Message.reply_poll`.
- Added the field ``can_react_to_messages`` to the :obj:`~pyrogram.types.ChatPermissions`.
