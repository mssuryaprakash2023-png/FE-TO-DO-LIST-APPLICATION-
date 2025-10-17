# To-Do-List Application

A modern, responsive web-based To-Do List application with complete CRUD (Create, Read, Update, Delete) operations. Built with vanilla HTML, CSS, and JavaScript.

## Features

### ✅ Complete CRUD Operations
- **CREATE**: Add new tasks with a clean input interface
- **READ**: View all tasks with filtering and search capabilities
- **UPDATE**: Edit existing tasks with a modal interface
- **DELETE**: Remove individual tasks or clear all completed tasks

### 🎨 Modern UI/UX
- Responsive design that works on desktop and mobile
- Beautiful gradient backgrounds and smooth animations
- Intuitive icons and visual feedback
- Clean, modern interface with hover effects

### 🔍 Advanced Features
- **Search**: Real-time search through all tasks
- **Filtering**: View All, Active, or Completed tasks
- **Statistics**: Live count of total, active, and completed tasks
- **Bulk Actions**: Mark all tasks as complete or clear completed tasks
- **Local Storage**: Data persists between browser sessions
- **Notifications**: Visual feedback for all actions

### 📱 Responsive Design
- Mobile-first approach
- Touch-friendly interface
- Optimized for all screen sizes

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required

### Installation

1. **Clone or Download** the project files:
   ```
   - index.html
   - styles.css
   - script.js
   - README.md
   ```

2. **Open the Application**:
   - Double-click `index.html` to open in your default browser
   - Or right-click `index.html` → "Open with" → Choose your preferred browser

3. **Start Using**:
   - The application will load with sample tasks to demonstrate features
   - Begin adding, editing, and managing your tasks immediately

## How to Use

### Adding Tasks (CREATE)
1. Type your task in the input field at the top
2. Click "Add Task" or press Enter
3. The task will appear in your list immediately

### Viewing Tasks (READ)
- **All Tasks**: Click "All" to see every task
- **Active Tasks**: Click "Active" to see incomplete tasks
- **Completed Tasks**: Click "Completed" to see finished tasks
- **Search**: Use the search box to find specific tasks

### Editing Tasks (UPDATE)
1. Hover over any task to see the "Edit" button
2. Click "Edit" to open the edit modal
3. Modify the task text
4. Click "Save Changes" or press Enter

### Deleting Tasks (DELETE)
1. **Single Task**: Hover over a task and click "Delete"
2. **All Completed**: Click "Clear Completed" button
3. **Mark All Complete**: Click "Mark All Complete" button

### Task Management
- **Complete Tasks**: Click the checkbox next to any task
- **Statistics**: View live counts at the top of the task list
- **Search**: Type in the search box to filter tasks in real-time

## Technical Details

### File Structure
```
ToDoListApplication/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality and CRUD operations
└── README.md           # This documentation file
```

### Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **Vanilla JavaScript**: No frameworks, pure ES6+ JavaScript
- **Local Storage**: Browser-based data persistence
- **Font Awesome**: Icons for better UX

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Features in Detail

### CRUD Operations
1. **Create**: Add new tasks with validation
2. **Read**: Display tasks with filtering and search
3. **Update**: Edit task text with modal interface
4. **Delete**: Remove tasks individually or in bulk

### Data Persistence
- All tasks are automatically saved to browser's local storage
- Data persists between browser sessions
- No server required - completely client-side

### User Experience
- Smooth animations and transitions
- Visual feedback for all actions
- Responsive design for all devices
- Keyboard shortcuts (Enter to add/save)

## Customization

### Adding New Features
The code is well-structured and commented, making it easy to extend:
- Add new task properties in the `addTodo()` method
- Modify the UI in `styles.css`
- Add new functionality in `script.js`

### Styling
- Colors and themes can be easily modified in `styles.css`
- The design uses CSS custom properties for easy theming
- Responsive breakpoints are clearly defined

## Troubleshooting

### Common Issues
1. **Tasks not saving**: Check if local storage is enabled in your browser
2. **Styling issues**: Ensure all files are in the same directory
3. **JavaScript errors**: Check browser console for error messages

### Browser Support
- Ensure JavaScript is enabled
- Use a modern browser for best experience
- Clear browser cache if experiencing issues

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to fork this project and submit pull requests for improvements!

---

**Enjoy organizing your tasks with this modern To-Do List Application!** 🎉
