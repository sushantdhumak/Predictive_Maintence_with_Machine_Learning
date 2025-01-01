---

### **Machine Learning for Predictive Maintenance**

---

#### **Brief Description**

This dataset reflects real predictive maintenance encountered in the industry with measurements from real equipments. The features description is taken directly from the dataset source.

Dataset Link:
https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset

---

#### **Feature Variables**

**Air temperature** [K]: Generated using a random walk process later normalized to a standard deviation of 2 K around 300 K

**Process temperature** [K]: Generated using a random walk process normalized to a standard deviation of 1 K, added to the air temperature plus 10 K.

**Rotational speed** [rpm]: Calculated from a power of 2860 W, overlaid with a normally distributed noise

**Torque** [Nm]: Torque values are normally distributed around 40 Nm with a Ïƒ = 10 Nm and no negative values.

**Tool wear** [min]: The quality variants H/M/L add 5/3/2 minutes of tool wear to the used tool in the process.

---

#### **Target Variables**

**Machine failure** : Failure or No failure (to perform binary classification)

**Failure Type**: Type of failure (to perform multiclass classification).

---

The machine failure type are as mentioned below

**Tool wear failure** (TWF): The tool will be replaced on failure

**Heat dissipation failure** (HDF): Heat dissipation causes a process failure

**Power failure** (PWF): The product of torque and rotational speed (in rad/s) equals the power required for the process.

**Overstrain failure** (OSF)

**Random failures** (RNF): Each process has a chance of 0,1 % to fail regardless of its process parameters.

----------------------------------------------------------------------

#### **Additional Variables**

**UID**: Unique identifier ranging from 1 to 10000

**Product ID**: Consists of letters L, M, or H for low (50% of all products), medium (30%) and high (20%) as product quality variants and a variant-specific serial number
