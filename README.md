# ELR-Mounting-Plate
A rugged, mounting solution for securely attaching electronic hit indicators to steel targets in extreme long-range (ELR) shooting setups. Designed for durability, repeatability, and easy integration with common target systems.
![IMG_20251123_082742701_HDR](https://github.com/user-attachments/assets/71474e92-9476-4694-b6de-e58567991f15)
![60 fps 00_00_09_03 Still001](https://github.com/user-attachments/assets/c5bb1caa-c459-4ffa-a8c3-293e78ec3cb2)
# Current Features/Capabilities
- 🔧 **Hybrid Mounting System**  
  Combines a large Velcro surface with two neodymium magnets for constant pressure against the steel plate.
  
- 🛡️ **Durable Materials**  
  - **ASA plastic**: UV and impact resistant, ideal for outdoor use.  
  - **TPU rubber**: Provides shock absorption and prevents shattering under repeated impacts.  

- 🎯 **Adaptable Design**  
  Compatible with multiple hit indicators:
  - Coriolis Hit Indicator (future project to be completed)
  - Caldwell Flash Bang  
  - MagnetoSpeed T1000  
  - Can be adapted to virtually any hit indicator with future iteration
# To build the ELR Mounting Plate, you will need the following components:

| Qty | Item | Description | Link |
|-----|------|-------------|------|
| 2   | Neodymium Magnets | 180 lb pull force, heavy-duty magnets for mounting pressure | [Amazon Product Page](https://www.amazon.com/MUTUACTOR-Neodymium-Magnets-Anti-Broken-Equipments/dp/B07JKWCVTX) |
| 4   | M4 Screws (20mm)  | Standard metric screws for securing ASA and TPU layers | — |
| 2   | M4 Screws (25mm)  | Longer screws for reinforced bracket mounting | — |
| 2   | M4 Screws (30mm)  | Extra-long screws for thicker assemblies | — |
| 26  | M4 Washers         | Flat washers to distribute load and prevent damage | — |
| 10  | M4 Lock Washers    | Locking washers to resist loosening under vibration/impact | — |
| 10  | M4 Nuts            | Standard nuts for fastening bolts | — |
| 2   | Velcro Adhesive Dots | 1.5” round industrial-strength adhesive fasteners for mounting | [Amazon Product Page](https://www.amazon.com/pson-Adhesive-Fasteners-Mounting-Industrial/dp/B0F4DZC5RM) |
| 1   | Velcro Pad (6x4”)  | Waterproof double-sided adhesive pad for larger mounting surface | [Amazon Product Page](https://www.amazon.com/Upgrade-Adhesive-Double-Side-Fastener-Waterproof/dp/B07D38TNF9) |
| 1   | Velcro Strap (1/2” wide) | Strap for securing Magneto Speed T1000 hit indicator | [Amazon Product Page](https://www.amazon.com/dp/B0CH8K8VWC) |
| 1   | Support Bar        | Tool for safely removing the mounting plate from steel targets | [Amazon Product Page](https://www.amazon.com/dp/B0DYF8F2RN) |
| 1   | TPU 95 Filament    | Flexible filament for impact-absorbing core | — |
| 1   | ASA Filament       | UV and impact-resistant filament for outer plates | — |


# Step 1: Printing the PLate
- Start by downloading the ELR Mounting PLate STL in the stl folder. The orientation of the plate is pictured below. This requires no support.
- ![full plate before splitting](https://github.com/user-attachments/assets/0c629984-20b7-471a-841c-5df1b2f76e2f)
- Next, we'll split the plate into 3 different layers: Two layers of ASA on the outside with a layer of TPU sandwiched in the middle. 
- The first cut will be performed horizontally with a depth of approximately 10.37 mm. It will be printed with ASA. 
- ![1st cut](https://github.com/user-attachments/assets/d6bfc7aa-6bcb-49da-a1a9-c1e62bed9815)
- ![1st Print ASA](https://github.com/user-attachments/assets/44106cfb-5d5c-4861-923c-52d12ef57059)

- The next cut will split the remainder of the plate exactly in half, leaving a thickness of about 5.76 mm for the remaining two plates. 
- The opposite outside layer will also be printed with ASA
- ![2nd Print ASA](https://github.com/user-attachments/assets/b6e7956a-e0fe-4cdd-a7c4-4d97547be5d1)

- The third print will be with TPU 95
- ![3rd Print TPU95](https://github.com/user-attachments/assets/4f4b708b-cb35-46c5-9d68-86251eb3565f)


## Printer Filament Settings

The ELR Mounting Plate uses a **multi-material print** combining ASA for rigidity and TPU95 for impact absorption. Below are the recommended slicer settings for each material:

### ASA (Outer Plates)
| Setting            | Value                  |
|--------------------|------------------------|
| Infill Percentage  | 30%                    |
| Infill Pattern     | Gyroid                 |
| Wall Passes        | 5                      |
| Bottom Shell Layers| 5                      |

**Notes:**  
- ASA provides UV resistance and high impact strength, making it ideal for outdoor shooting environments.  
- Higher wall count and bottom layers ensure structural rigidity around magnet mounts and screw holes.  
- Gyroid infill balances strength with weight reduction.  

---

### TPU95 (Inner Core)
| Setting            | Value                  |
|--------------------|------------------------|
| Infill Percentage  | 10%                    |
| Infill Pattern     | Gyroid                 |
| Wall Passes        | 3                      |
| Bottom Shell Layers| 3                      |

**Notes:**  
- TPU95 acts as a shock absorber, preventing cracks and distributing impact forces.  
- Lower infill keeps the core flexible while still providing support.  
- Gyroid infill maintains elasticity and impact resistance.  

---

### Why These Settings?
- **ASA + TPU95 Hybrid:** The rigid ASA shell protects against environmental stress, while the TPU95 core absorbs repeated impacts.  
- **Gyroid Infill:** Provides isotropic strength and flexibility, superior to grid or honeycomb for impact-heavy applications.  
- **Wall Passes & Shell Layers:** Extra walls in ASA prevent shattering, while fewer walls in TPU maintain flexibility.  

