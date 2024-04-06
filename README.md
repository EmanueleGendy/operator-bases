# Yukawa Invariants Generator

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

```
}
