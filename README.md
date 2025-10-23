# Acid-Base Chemistry Experiment Simulator

A web-based interactive chemistry simulator that demonstrates acid-base reactions, ion dissociation, and pH calculations. Built with HTML5, CSS, JavaScript, and p5.js.

## Features

- **Interactive Particle View**: Visual representation of ions as animated colored particles
- **Five Chemistry Experiments**:
  1. HCl dissociation (strong acid)
  2. NaOH dissociation (strong base) 
  3. HCl + NaOH neutralization
  4. HCl + NH₃ (acidic salt formation)
  5. CH₃COOH + NaOH (basic salt formation)
- **Real pH Calculations**: Accurate chemistry calculations using equilibrium constants
- **Workbook-Style Output**: Formatted results matching laboratory workbook format
- **Responsive Design**: Works on desktop and mobile devices

## How to Host on GitHub Pages

1. **Create a new repository** on GitHub
2. **Upload the files**:
   - `index.html`
   - `README.md`
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
4. **Access your app** at: `https://yourusername.github.io/your-repository-name`

## How to Use the Application

1. **Open the application** in a web browser
2. **Select an experiment** by clicking one of the buttons:
   - Step 1: HCl Dissociation
   - Step 1: NaOH Dissociation  
   - Step 2: HCl + NaOH Neutralization
   - Step 3: HCl + NH₃ (Acidic Salt)
   - Step 3: CH₃COOH + NaOH (Basic Salt)
3. **Observe the results**:
   - **Left panel**: Animated particle view showing ions as colored dots
   - **Right panel**: Workbook-style output with calculations and observations
4. **Use "Clear Canvas"** to reset between experiments

## Ion Color Legend

- 🔴 **Red**: H⁺ (Hydrogen ions)
- 🟢 **Green**: Cl⁻ (Chloride ions)  
- 🔵 **Blue**: Na⁺ (Sodium ions)
- 🟣 **Purple**: OH⁻ (Hydroxide ions)
- 🟠 **Orange**: NH₄⁺ (Ammonium ions)
- 🟡 **Yellow**: CH₃COO⁻ (Acetate ions)

## Chemistry Calculations

The simulator uses these equilibrium constants:
- **Kw** = 1.0 × 10⁻¹⁴ (water dissociation)
- **Ka(NH₄⁺)** = 5.6 × 10⁻¹⁰ (ammonium hydrolysis)  
- **Kb(CH₃COO⁻)** = 5.6 × 10⁻¹⁰ (acetate hydrolysis)

pH calculations assume:
- 1M initial concentrations
- Equal volumes (1L each) for mixing reactions
- 0.5M final salt concentrations after neutralization

## Technical Details

- **Technologies**: HTML5, CSS3, JavaScript, p5.js (CDN)
- **Canvas Size**: 400×400 pixels
- **Particle Count**: ~20 particles per 1M concentration
- **Animation**: Particles move randomly within canvas bounds
- **No Dependencies**: All resources loaded via CDN, no server required

## Browser Compatibility

Tested and compatible with:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Local Development

Simply open `index.html` in any modern web browser - no server required!

## License

This project is open source and available under the MIT License.