# Fingerprint Sensor Theme

## Hiyuki Fingerprint Customization

### Components:
- `fingerprint_config.json` - Fingerprint configuration
- `icons/` - Fingerprint scanner icons
- `effects/` - Animation effects for fingerprint scanning

### Animation Effects:

#### Scan Animation
- 20 animation frames
- Red wave pattern (#C41E3A)
- Wave propagates from center outward
- Smooth continuous motion

#### Success Animation
- Name: "hiyuki_glow"
- Duration: 500ms
- Hiyuki character glow effect
- Red particles burst outward

#### Failed Animation
- Name: "red_x"
- Duration: 400ms
- Red X appears and shakes
- Transitions smoothly

### Advanced Effects:
- **Scan Wave**: Circular wave effect during scanning
- **Particle Effect**: Red particles for success/failure feedback
- **Color Theme**: All effects use #C41E3A (Hiyuki red)

### Animation Files Structure:
- `scan_0.png` to `scan_19.png` (20 frames total)
- `success_0.png` to `success_9.png` (10 frames)
- `failed_0.png` to `failed_4.png` (5 frames)
