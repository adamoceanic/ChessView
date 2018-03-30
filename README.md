# ChessVision
An application that can detect and analyse a position on a real chessboard via a smartphone camera

There a handful of okay(ish) OCR based apps that can scan a printed diagram of a chessboard in the classic top-down orientation from a magazine or pdf and then produce a FEN or PGN representation of the position. However, there have been a number of recent occasions throughout my chess career where I have been involved in a non-digital friendly or training game and I've found myself wanting to analyse a position as a learning oppurtinity but my analysis laptop with ChessBase etc on it has been elsewhere and I've have to resort to taking a photo on my phone or committing it to memory. 
<br />
<br />
This project is an attempt to combine the scanner apps that exist thus far, with real over the board play. My ideal scenario is for a user to be able to take a picture of the position from a viewing angle as close to how it is naturally through the user's eyes and then for the application to correctly derive the position, translate it into the desired game notation, and then provide on the spot analysis via an engine. One step further could even be the ability to augment the image with some positional guidance like best move and potential warning indicators to turn it into a dynamically useful training aid. From experience, I am aware that the cost of having a dedicated chess laptop with up-to-date analysis engines and game databases can run into the thousands. If this smartphone app can make that kind of training aid more accessible to the equally as capable but less fortunate player then it will be a worthy project. I predict problems, pitballs, and nightmares aplenty, but I'll keep grinding until I get it done.

## Technology
Nothing is set in stone but I predict a blend of OpenCV, Tensorflow, Stockfish, and whatever I need for the OSX and Android SDKs.

## High-level Plan
Coming soon.
