# Blink Battle

A no-login, cross-device reflex game for 2–8 people.

## Play

1. One person hosts a room and shares its eight-character code.
2. Everyone joins from their own phone or computer.
3. The host starts five rounds. Wait through the countdown; tap only when the signal turns green.
4. An early tap sits out that round and costs a point when possible. The quickest valid reaction takes the round point. First to three wins; after five rounds, the highest score wins.

## How multiplayer works

The host owns the scoreboard and round sequence. PeerJS Cloud brokers peer discovery; after peers connect, WebRTC data channels carry room events directly between browsers where network conditions permit. The host tab must remain open. Public PeerJS signaling and the pinned PeerJS browser library are external services/dependencies.

No accounts, camera, microphone, persistence, or personal details are required. Player-entered nicknames and game events are shared with the room. No game history is stored after a tab closes.
