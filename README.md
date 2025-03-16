# ♟️ ChessPredictionProject - Ongoing  

**ChessPredictionProject** enables real-time chess analysis and move optimization to gain an advantage in a game. Using your mobile camera to scan the chessboard, it detects the current board state, analyzes positions, and suggests the best moves. By leveraging **YOLO** for piece detection and **Stockfish** for strategic insights, the system delivers powerful recommendations to help you navigate the game and make optimal moves toward victory.  

---

## 🚀 Features  

✅ **Real-Time Chessboard Detection** – Uses YOLO to identify pieces on the board.  
✅ **Move Optimization** – Integrates Stockfish to suggest the best moves.  
✅ **Mobile Camera Support** – Capture the board state using an **IP Webcam**.  
✅ **Video Analysis** – Option to analyze pre-recorded chess games.  
✅ **FEN Generation** – Converts board positions into Forsyth-Edwards Notation (FEN).  

---

## 🛠️ Tech Stack  

- **Object Detection:** YOLO  
- **Chess Engine:** Stockfish  
- **Programming Language:** Python  
- **Notebook Environment:** Jupyter Notebook (`.ipynb`)  
- **Video Processing:** OpenCV  
- **Mobile Camera Input:** IP Webcam  

---

## 📦 How to Initialize the Project  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/ChessPredictionProject.git
cd ChessPredictionProject
```
2️⃣ Create a Virtual Environment (Python 11 or Below)
```sh
Copy
Edit
python -m venv chess_env
source chess_env/bin/activate  # On macOS/Linux
chess_env\Scripts\activate     # On Windows
```
3️⃣ Install Dependencies
```sh
Copy
Edit
pip install -r requirements.txt
```
4️⃣ Open the Jupyter Notebook
```sh
Copy
Edit
jupyter notebook
Then, open Video.ipynb in Jupyter Notebook.
```
5️⃣ Set Up IP Webcam (For Live Camera Input)
```sh
Download IP Webcam from the Play Store.
Start the IP Webcam server on your phone.
Copy the IP address from the app.
Update the address field in the 2nd cell of Video.ipynb.
```
6️⃣ Run the Notebook
```sh
For Live Camera Input: Run the first two cells.
For Video Input (Optional): Execute the third cell instead.
```
## 🔥 Contribution Guidelines
-Fork the repository and create a new branch for your feature.
-Make the necessary changes and commit them with a meaningful message.
-Push your changes and create a pull request (PR).
-Wait for review and merge approval.
-Check the Issues section for new feature requests or bug reports.

## 🤝 Support
-If you encounter any issues or have suggestions for improvement, feel free to raise an issue or contact me at your-email@example.com.
-Let's take chess analysis to the next level! ♞🔍

## 📜 License
-This version is **cleaner, more structured, and professional**, making it easier for users to understand and use your project. Let me know if you need any more changes! ♟️🚀







