# Redux Basic Example

This is a simple React project demonstrating basic usage of Redux for state management, built with Vite.

## Features
- Counter example using Redux Toolkit
- Organized folder structure for scalability
- Fast development with Vite

## Project Structure
```
src/
	App.jsx           # Main app component
	index.css         # Global styles
	main.jsx          # Entry point
	app/
		store.js        # Redux store setup
		features/
			counter/
				counterSlice.js # Counter slice
	components/
		Counter.jsx     # Counter UI component
```

## Getting Started

1. **Install dependencies:**
	 ```powershell
	 npm install
	 ```
2. **Start the development server:**
	 ```powershell
	 npm run dev
	 ```
3. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Usage
- Click the increment/decrement buttons to update the counter using Redux state.

## Technologies Used
- React
- Redux Toolkit
- Vite


