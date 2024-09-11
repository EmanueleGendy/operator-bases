<<<<<<< HEAD
# Invariants Generator

This Python script generates invariants built out of Yukawa matrices and one instance of a SMEFT dimension-6 coefficient up to a specified degree. Then it checks if, at the chosen degree, there exists a relation between them\

## Features

- Generates invariants up to a specified degree.
- Checks if there is there is a relation between the invariants by building a linear system of invariants and checking if there is any null vector. 

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/yukawa-invariants.git
   ```

2. Navigate to the project directory:

   ```bash
   cd yukawa-invariants
   ```

3. Install the required dependencies:

   ```bash
   pip install numpy scipy sympy
   ```

## Usage

1. Run the `yukawa_invariants.py` script:

   ```bash
   python yukawa_invariants.py
   ```

2. Follow the on-screen prompts to specify the degree of Yukawa invariants and input matrices.

3. The script will generate Yukawa invariants and compute the nullspace of the resultant matrices.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch:

   ```bash
   git checkout -b feature/my-feature
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add my feature"
   ```

4. Push to the branch:

   ```bash
   git push origin feature/my-feature
   ```

5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please feel free to reach out to Emanuele Gendy (mailto:emanuele.gendy@gmail.com).
=======
# Matrix Invariant Relations

This Mathematica notebook explores algebraic relations between matrix invariants built from combinations of Yukawa coupling matrices and a "spurion" matrix in the context of SMEFT at dimension-6. It has to be understood as the notebook accompanying Appendix B.4 of arXiv:2112.03889.

## Description

The code performs the following main tasks:

1. Constructs independent invariant traces built solely from Yukawa matrices up to a specified dimension.
2. Constructs invariant traces linear in the spurion matrix by combining Yukawa invariants with powers of the spurion.
3. Combines these two sets of invariants into products such that their total dimension adds up to a specified value.
4. Finds linear relations among these product invariants by solving for coefficient vectors that make their linear combinations vanish.
5. Displays the derived linear relations between the invariant traces.

## Prerequisites

This notebook requires the following packages:

- `TensorSimplify`

This package can be found at (and it is entirely credited to): https://github.com/carlwoll/TensorSimplify

To install `TensorSimplify`, run the following command in Mathematica:

```mathematica
PacletInstall[
    "TensorSimplify", 
    "Site" -> "http://raw.githubusercontent.com/carlwoll/TensorSimplify/master"
]
```
Once installed, you can load the paclet as usual:
<<TensorSimplify`

## Usage

1. Open the notebook file in Mathematica.
2. Ensure that the `TensorSimplify` package is loaded by evaluating the first cell: `<< TensorSimplify`
3. Evaluate the remaining cells in order to execute the code.
4. Adjust the values of `deg` and `degree` to change the maximum dimensions of the invariants considered.
5. The derived linear relations between the invariant traces will be displayed in a formatted grid output.

## Notes

- This code is intended for exploring theoretical physics concepts and may require knowledge of the underlying model and context for full interpretation (see arXiv:2112.03889
for more details).
- The code currently lacks user input/output handling and error checking, making it more suitable for personal use or reference.
- Contributions to improve documentation, user-friendliness, and code quality are welcome. Please send any suggestions to emanuele.gendy@gmail.com .

## License

This code is released under the [MIT License](LICENSE).
>>>>>>> second-repo/main
