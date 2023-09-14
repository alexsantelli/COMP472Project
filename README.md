# COMP472Project

## Tasks for D1

### H-H

Every Unit has 9 health (value 0-9) Int

- Create Attacker: 1×AI, 2×Viruses, 2× Programs and 1×Firewall;
- Create Defender: 1×AI, 2×Techs, 2×Firewalls and 1×Program;

#### Attacks and Repairs

![image](https://github.com/alexsantelli/COMP472Project/assets/87946958/2057e3d1-3382-4f6f-81ab-ec81195612a5)

### Initial Configuration (How Game Starts)

![image](https://github.com/alexsantelli/COMP472Project/assets/87946958/3aadb9ae-5e76-4bea-b16d-933423242128)

### Movement
- Check if a space is free
- Engaged in Combat -> Adjacent (up and down) (left and right)
- AI, Firewall, Program in combat-> can NOT move
- Virus & Tech, in combat -> Can move

Attackers
- AI, Firewall, Program -> move up and left
- Virus & Tech -> move up, down, left, right

Defenders
- AI, Firewall, Program -> move down and right
- Virus & Tech -> move up, down, left, right

Note: When attacking, must be adjacent and adversarial units & (Bi-directional damage)

### Repair
See Table 2 above

### Self Destruct
- Any unit can self-destruct
- Damages 2 points around itself
