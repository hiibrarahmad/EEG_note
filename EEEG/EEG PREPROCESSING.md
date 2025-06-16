### 🎯 **Most important features for in-ear EEG (stress, attention, cognitive load)**

👉 Focus on features that are **robust**, **low-SNR-tolerant**, and **validated for ear-EEG**:

---

#### 1️⃣ **Relative Band Power (normalized to reduce inter-subject variability)**

- **Theta (4–8 Hz)**
    
    - Still useful for cognitive load / mental effort detection.
        
    - Frontal midline theta may be weaker, but general theta band changes are detectable.
        
- **Alpha (8–12 Hz)**
    
    - Alpha suppression is still meaningful for attention / relaxation balance.
        
    - Focus on changes in relative alpha (not absolute values).
        
- **Beta (13–30 Hz)**
    
    - Useful for stress and engagement (especially low-beta ~13–20 Hz).
        
    - Avoid overinterpreting high-beta; may have contamination from EMG.
        
- **Gamma (>30 Hz)**
    
    - Often hard to trust in ear-EEG due to artifact. Skip unless hardware is very good.
        

---

#### 2️⃣ **Ratios**

- **Theta / Beta ratio**
    
    - Still meaningful for attention and mental fatigue.
        
- **Beta / Alpha or (Beta + low Gamma)/(Alpha + Theta)**
    
    - Gives stress or arousal signal. Ear-EEG studies confirm this can work.
        

---

#### 3️⃣ **Temporal Entropy / Complexity Measures**

- **Sample Entropy**, **Spectral Entropy**
    
    - Good for detecting cognitive load because they reflect overall neural variability.
        
    - Less sensitive to precise regional origin → works better for ear-EEG.
        
- **Hjorth Mobility & Complexity**
    
    - Quick to compute, useful for in-ear form factors.
        

---

#### 4️⃣ **Slow Wave Index (delta + theta combined power)**

- Because in-ear EEG may pick up sleepiness / overload via slower activity better than isolated band measures.
    

---

#### 5️⃣ **Power asymmetry across ears**

- If you have bilateral ear-EEG:
    
    - Left vs. right alpha power → basic mood/arousal asymmetry
        
    - Left vs. right beta power → engagement asymmetry



