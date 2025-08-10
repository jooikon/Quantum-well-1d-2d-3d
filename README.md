# 🌀 Quantum-Well Solver (1-D / 2-D / 3-D)

Beginner-level quantum-mechanics project in Python

---

## 📊 Dataset Overview
**Dataset:** none required – eigenvalues and wavefunctions are computed on-the-fly.

| Column | Description |
|--------|-------------|
| dimension | 1-D / 2-D / 3-D |
| level | quantum number n |
| energy | eigen-energy (eV) |

---

## 🛠️ Tools Used
- Python 3  
- NumPy & SciPy (sparse linear algebra)  
- Matplotlib for plots  
- Jupyter Lab  

---

## 📈 Key Insights
- 1-D finite well: first 5 bound states agree with analytical formula  
- 2-D square well: degeneracy pattern 1-2-3-4…  
- 3-D cubic well: lowest 10 levels computed on a 40³ grid

---

## 📚 What I learned
- Constructing Hamiltonian with finite-difference stencils  
- Handling sparse matrices (scipy.sparse)  
- Visualising |ψ|² heat-maps in 2-D and mid-plane slices in 3-D  
- Energy-level statistics vs dimensionality

---

## 💡 Next steps
- Add time-evolution (split-operator)  
- Compare different well shapes (circular, parabolic)  
- Interactive dashboard with ipywidgets

---

## 🚀 Run it yourself
```bash
git clone https://github.com/YOUR_USERNAME/quantum-well-1d-2d-3d.git
cd quantum-well-1d-2d-3d
pip install -r requirements.txt
jupyter lab
