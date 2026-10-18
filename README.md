# Mala Noodle Timer

My first university Python project, created in **2024 (B.E. 2567)** for the **Problem Solving and Computer Programming (PSCP)** course, semester 1 of the 2024 academic year.

A simple countdown timer for cooking mala noodles, built with Python and Tkinter. This project applies introductory programming concepts to an everyday task: tracking different cooking times for different types of noodles.

## About the Project

The program accepts a noodle name through console input and displays a countdown in both a Tkinter window and the console. It includes four noodle presets and allows users to enter a custom duration for other noodles.

When the countdown finishes, it displays `!!Finish!!` and the Thai message `พร้อมรับประทานแล้ว :D` (Ready to eat).

Developed for course **06066303**, Faculty of Information Technology, Data Science and Business Analytics program, **King Mongkut's Institute of Technology Ladkrabang (KMITL)**.

## Features

- Four noodle presets with predefined countdown durations.
- Custom durations entered in minutes and seconds.
- A desktop window showing the noodle name and remaining time in `MM:SS` format.
- Countdown updates scheduled through Tkinter's `window.after()`.
- A completion message in the window and console.

## Noodle Presets

Enter the names exactly as shown, including capitalization and spaces.

| Noodle name | Duration configured in the code |
| --- | --- |
| `Sweet Potato Noodles` | 7 minutes |
| `Glass Noodles` | 7 minutes |
| `Konjac Noodles` | 5 minutes |
| `Fern Root Noodles` | 10 minutes |

## Built With

- **Python 3** for input handling, conditional logic, and time calculations.
- **Tkinter** for the countdown window.
- **Jupyter Notebook** for storing and running the code.

The original notebook metadata records Python **3.12.4**.

## Project Files

```text
.
├── README.md
└── Mala Project.ipynb
└── docs/
    ├── Mala Project Report.pdf
    └── Malha Final Present.pdf
```

- [Mala Project.ipynb](Project%20PSCP/Mala%20Project.ipynb): countdown timer source code.
- [Mala Project Report.pdf](Project%20PSCP/Mala%20Project%20Report.pdf): project background, objectives, design, and results (in Thai).
- [Malha Final Present.pdf](Project%20PSCP/Malha%20Final%20Present.pdf): project presentation slides (primarily in Thai).
- [DESCRIPTION.md](DESCRIPTION.md): short project descriptions in Thai and English.

## Getting Started

Use a local Python environment with Tkinter and desktop GUI support. Open the notebook with Jupyter Notebook or VS Code with the Python and Jupyter extensions.

1. Check that Tkinter is available:

   ```bash
   python -m tkinter
   ```

   A test window should appear. Close it before running the project.

2. If needed, install and launch Jupyter Notebook:

   ```bash
   python -m pip install notebook
   python -m notebook
   ```

3. Open `Project PSCP/Mala Project.ipynb` and select your local Python kernel.
4. Run the cells in order. At `Enter your noodle :`, enter a noodle name from the table above.
5. Run the remaining cells to open the `Timer` window and start the countdown.
6. For a custom duration, enter another name, such as `Custom`. When the final cell runs, enter the number of **minutes**, then the number of **seconds**, as two separate integer inputs. These inputs have no prompt labels. For a quick five-second trial, enter `0` and then `5`.
7. When the countdown finishes, close the timer window to end the GUI session before starting another run.

This repository preserves an early learning project and marks the beginning of my university Python journey in 2024!
