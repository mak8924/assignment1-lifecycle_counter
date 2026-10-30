# ⏱️ UMS Flutter Mobile Development - Advanced Counter & Lifecycle Assignment

A comprehensive Flutter practical application demonstrating state management, interactive periodic timers, and deep lifecycle analysis of `StatefulWidget` (`initState` and `dispose`) to ensure clean memory management.

---

## 🚀 Key Features Implemented

1. **StatefulWidget Lifecycle Analysis**:
   - Proper initialization of state properties during the widget setup phase (`initState`).
   - Clean destruction and resource cleanup when the widget is unmounted (`dispose`).

2. **Periodic Timer Management (`Timer.periodic`)**:
   - Automated real-time counter incrementing every second.
   - Interactive timer controls: **Play**, **Pause**, and **Reset**.

3. **Memory Leak Prevention**:
   - Explicit cancellation of active timers inside `dispose()` to prevent memory leaks and unhandled background processes.

4. **Dynamic UI Rendering**:
   - Reactive UI updates using `setState` with disabled/enabled button states reflecting current timer conditions.

---

## 🛠️ Tech Stack & Architecture

- **Framework**: Flutter (Dart)
- **State Management**: `StatefulWidget` (`initState`, `setState`, `dispose`)
- **Async & Timers**: Dart `async` & `Timer.periodic`
- **UI Components**: `Scaffold`, `ElevatedButton.icon`, `Column`, `Row`

---

## ⚙️ How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/counter_assignment.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd counter_assignment
   ```

3. **Fetch dependencies**:
   ```bash
   flutter pub get
   ```

4. **Run on connected device/emulator**:
   ```bash
   flutter run
   ```