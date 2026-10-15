# CS683: Advanced Computer Architecture
## Programming Assignment 2: Memory Hierarchy Optimization

### Team Information
- **Team Name**: Picasso
- **Team Members**:
  - Ansh Agrawal (24B0909)
  - Saksham Khandelwal (24B0965)
  - Sangye Norphel Sherpa (24B1050)
  - Ayush Katiyar (24B1268)

### Build Instructions
```bash
# Task 1B: SPP Prefetcher
./build_champsim.sh spp lru spp

# Task 2A: I-RRIP L2 Replacement
./build_champsim.sh no irrip irrip

# Task 2B: Dynamic I-RRIP (Set Dueling)
./build_champsim.sh no dyn_irrip dyn_irrip

# Task 3: SPP + Dynamic I-RRIP
./build_champsim.sh spp dyn_irrip spp_dyn_irrip
```
