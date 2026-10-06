# Menu first-row clipping reproduction

These are native Qt screenshots of a controlled ListView fixture. They are not captures of the user's desktop. Each runs revealCursor() from Menu.qml directly while the viewport grows from 50 to 450 pixels, without a later guard-driven model rebuild. The original clips Apps; the corrected function places it at the top immediately. The reporter also confirmed the local correction in the real Omarchy menu.
