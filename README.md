# <img src="docs/brand/mark.svg" width="40" height="40" align="top" alt=""> Modbus Register Maps

Open, machine-readable Modbus register maps for energy meters, inverters, drives and other field devices.
Each device is one YAML file with the address, data type, byte order, unit and scale of every register, and the
document it was transcribed from.

![Modbus Register Maps: every register, with its source](docs/brand/social-preview.png)

Vendor manuals bury this in PDF tables with mixed addressing conventions (30001, 0x0000, "register 1"). Here
every address is the zero-based value sent on the wire, and the 30001-style reference is derived from it, so the
two can never disagree.

## Devices

<!-- catalog:start -->
| Vendor | Model | Category | Registers | Hardware-verified |
|---|---|---|---|---|
| ABB | [A43/A44](devices/abb/a43-a44.yaml) | energy-meter | 166 | not yet |
| ABB | [ACS580](devices/abb/acs580.yaml) | vfd | 31 | not yet |
| ABB | [ACS880](devices/abb/acs880.yaml) | vfd | 28 | not yet |
| ABB | [B23/B24](devices/abb/b23-b24.yaml) | energy-meter | 121 | not yet |
| ABB | [M4M 20/M4M 30](devices/abb/m4m-20-m4m-30.yaml) | power-analyzer | 228 | not yet |
| Carlo Gavazzi | [EM111/EM112](devices/carlo-gavazzi/em111-em112.yaml) | energy-meter | 48 | not yet |
| Carlo Gavazzi | [EM210](devices/carlo-gavazzi/em210.yaml) | energy-meter | 65 | not yet |
| Carlo Gavazzi | [EM24-DIN](devices/carlo-gavazzi/em24-din.yaml) | energy-meter | 78 | not yet |
| Carlo Gavazzi | [EM24-IS](devices/carlo-gavazzi/em24-is.yaml) | energy-meter | 30 | not yet |
| Carlo Gavazzi | [EM330/ET330](devices/carlo-gavazzi/em330-et330.yaml) | energy-meter | 74 | not yet |
| Carlo Gavazzi | [EM340/ET340](devices/carlo-gavazzi/em340-et340.yaml) | energy-meter | 82 | not yet |
| Danfoss | [VLT AQUA Drive FC 202](devices/danfoss/vlt-aqua-drive-fc-202.yaml) | vfd | 19 | not yet |
| Danfoss | [VLT AutomationDrive FC 302](devices/danfoss/vlt-automationdrive-fc-302.yaml) | vfd | 19 | not yet |
| Danfoss | [VLT HVAC Drive FC 102](devices/danfoss/vlt-hvac-drive-fc-102.yaml) | vfd | 20 | not yet |
| Eastron | [SDM120-Modbus](devices/eastron/sdm120-modbus.yaml) | energy-meter | 32 | not yet |
| Eastron | [SDM120CT-M](devices/eastron/sdm120ct-m.yaml) | energy-meter | 35 | not yet |
| Eastron | [SDM630-Modbus](devices/eastron/sdm630-modbus.yaml) | energy-meter | 97 | not yet |
| Eastron | [SDM630MCT](devices/eastron/sdm630mct.yaml) | energy-meter | 83 | not yet |
| Eastron | [SDM72D-M](devices/eastron/sdm72d-m.yaml) | energy-meter | 16 | not yet |
| Fronius | [Primo GEN24 Plus/Symo GEN24 Plus](devices/fronius/primo-gen24-plus-symo-gen24-plus.yaml) | inverter | 224 | not yet |
| Fronius | [Primo GEN24/Symo GEN24](devices/fronius/primo-gen24-symo-gen24.yaml) | inverter | 178 | not yet |
| Fronius | [Smart Meter](devices/fronius/smart-meter.yaml) | energy-meter | 73 | not yet |
| Fronius | [Tauro ECO](devices/fronius/tauro-eco.yaml) | inverter | 168 | not yet |
| Fronius | [Tauro](devices/fronius/tauro.yaml) | inverter | 188 | not yet |
| Fronius | [Verto 3 MPPT](devices/fronius/verto-3-mppt.yaml) | inverter | 188 | not yet |
| Fronius | [Verto 4 MPPT](devices/fronius/verto-4-mppt.yaml) | inverter | 198 | not yet |
| Fronius | [Verto Plus](devices/fronius/verto-plus.yaml) | inverter | 234 | not yet |
| Janitza | [UMG 103-CBM](devices/janitza/umg-103-cbm.yaml) | energy-meter | 53 | not yet |
| Janitza | [UMG 509-PRO](devices/janitza/umg-509-pro.yaml) | power-analyzer | 61 | not yet |
| Janitza | [UMG 604-PRO](devices/janitza/umg-604-pro.yaml) | power-analyzer | 61 | not yet |
| Janitza | [UMG 96-PA](devices/janitza/umg-96-pa.yaml) | power-analyzer | 54 | not yet |
| Janitza | [UMG 96-RM-E](devices/janitza/umg-96-rm-e.yaml) | power-analyzer | 61 | not yet |
| Janitza | [UMG 96-RM](devices/janitza/umg-96-rm.yaml) | power-analyzer | 61 | not yet |
| Klemsan | [KLEA 320P](devices/klemsan/klea-320p.yaml) | power-analyzer | 48 | not yet |
| Klemsan | [KLEA 4](devices/klemsan/klea-4.yaml) | power-analyzer | 43 | not yet |
| Klemsan | [KLEA 6](devices/klemsan/klea-6.yaml) | power-analyzer | 49 | not yet |
| Lovato Electric | [DMG110](devices/lovato-electric/dmg110.yaml) | power-analyzer | 55 | not yet |
| Lovato Electric | [DMG210](devices/lovato-electric/dmg210.yaml) | power-analyzer | 55 | not yet |
| Lovato Electric | [DMG800](devices/lovato-electric/dmg800.yaml) | power-analyzer | 54 | not yet |
| Schneider Electric | [ATV320](devices/schneider-electric/atv320.yaml) | vfd | 1071 | not yet |
| Schneider Electric | [ATV340](devices/schneider-electric/atv340.yaml) | vfd | 1741 | not yet |
| Schneider Electric | [ATV600](devices/schneider-electric/atv600.yaml) | vfd | 1879 | not yet |
| Schneider Electric | [ATV61](devices/schneider-electric/atv61.yaml) | vfd | 852 | not yet |
| Schneider Electric | [ATV71](devices/schneider-electric/atv71.yaml) | vfd | 926 | not yet |
| Schneider Electric | [ATV900](devices/schneider-electric/atv900.yaml) | vfd | 1911 | not yet |
| Schneider Electric | [EM6400NG](devices/schneider-electric/em6400ng.yaml) | power-analyzer | 424 | not yet |
| Schneider Electric | [iEM3000](devices/schneider-electric/iem3000.yaml) | energy-meter | 98 | not yet |
| Schneider Electric | [ION7400](devices/schneider-electric/ion7400.yaml) | power-analyzer | 807 | not yet |
| Schneider Electric | [ION9000](devices/schneider-electric/ion9000.yaml) | power-analyzer | 845 | not yet |
| Schneider Electric | [PM2100/PM2200](devices/schneider-electric/pm2100-pm2200.yaml) | power-analyzer | 679 | not yet |
| Schneider Electric | [PM3250/PM3255](devices/schneider-electric/pm3250-pm3255.yaml) | power-analyzer | 267 | not yet |
| Schneider Electric | [PM5100/PM5300](devices/schneider-electric/pm5100-pm5300.yaml) | power-analyzer | 877 | not yet |
| Schneider Electric | [PM5500/PM5600/PM5700](devices/schneider-electric/pm5500-pm5600-pm5700.yaml) | power-analyzer | 3108 | not yet |
| Schneider Electric | [PM8000](devices/schneider-electric/pm8000.yaml) | power-analyzer | 809 | not yet |
| Siemens | [PAC2200](devices/siemens/pac2200.yaml) | power-analyzer | 79 | not yet |
| Siemens | [PAC2200CLP](devices/siemens/pac2200clp.yaml) | power-analyzer | 81 | not yet |
| Siemens | [PAC3200](devices/siemens/pac3200.yaml) | power-analyzer | 151 | not yet |
| Siemens | [PAC3220](devices/siemens/pac3220.yaml) | power-analyzer | 91 | not yet |
| Siemens | [PAC4200](devices/siemens/pac4200.yaml) | power-analyzer | 222 | not yet |
| Siemens | [SINAMICS G120C](devices/siemens/sinamics-g120c.yaml) | vfd | 63 | not yet |
| Siemens | [SINAMICS V20](devices/siemens/sinamics-v20.yaml) | vfd | 77 | not yet |
| SMA | [Sunny Tripower Smart Energy](devices/sma/sunny-tripower-smart-energy.yaml) | inverter | 31 | not yet |
| SolarEdge | [Meter via Inverter](devices/solaredge/meter-via-inverter.yaml) | energy-meter | 37 | not yet |
| SolarEdge | [SunSpec Inverter](devices/solaredge/sunspec-inverter.yaml) | inverter | 41 | not yet |
<!-- catalog:end -->

"Hardware-verified" means someone read the registers from a real device and recorded it under `verified`.
The other maps are transcribed from the sources they list. Have one of these devices? A verification is one of the
most useful contributions you can make.

## Format

```yaml
schema_version: 1
vendor: Eastron
model: SDM630-Modbus
category: energy-meter
summary: Three-phase DIN-rail energy meter with RS485 Modbus RTU; every value is a 32-bit float.
connection:
  interfaces: [rtu]
  default_unit_id: 1
  default_byte_order: ABCD
sources:
  - title: Eastron SDM630Modbus Smart Meter Modbus Protocol Implementation
    publisher: Eastron
    version: V1.8
    url: https://...
registers:
  - key: voltage_l1_n
    name: Phase 1 line to neutral voltage
    table: input        # coil, discrete_input, input or holding
    address: 0          # zero-based protocol address (reference 30001)
    type: float32       # bool, int16, uint16, int32, uint32, float32, int64, uint64, float64, string, bitfield16
    unit: V
    access: r
```

Optional per register: `byte_order` (ABCD, CDAB, BADC, DCBA), `scale` (engineering value = raw × scale),
`scale_factor` (key of a register holding a power-of-ten exponent, as SunSpec devices use), `length` (for `string`,
`bitfield` and `raw`),
`values` (meaning of enumerated values), `applies_to` (wiring modes), `group`, `description` and `notes`.
The full contract is [schema/device.schema.json](schema/device.schema.json).

## Use the data

`python3 tools/maps.py build` writes `dist/index.json` and one JSON file per device. Each register gains its
30001-style `reference`, `address_hex`, Modbus `function_code`, effective `byte_order` and a
`proxus_mcp_address`.

The last one plugs into [Proxus Industrial MCP Server](https://github.com/proxus-io/proxus-mcp), which
lets AI assistants such as Claude read Modbus devices. With a map at hand you can ask:

> Read ir:52 on meter-1 as float32 ABCD. It's the total active power of an Eastron SDM630.

## Contribute

Adding a device takes one YAML file and a pull request; a check runs on every pull request and explains anything
that needs fixing. See [CONTRIBUTING.md](CONTRIBUTING.md). No device of your own? Ask for one with a
[device request](../../issues/new?template=device-request.yml).

## Corrections and removal requests

Maps record facts (addresses, data types, units) in this project's own format and words, with a link to the
document they come from. Vendor documents themselves are never stored here.

Found a wrong register? Open an issue or a pull request with the source or a reading that shows it. If you represent
a manufacturer and want a map corrected, linked to a newer document or removed, open an issue or contact the
maintainers through the repository owner's GitHub profile; requests are handled within five working days.

## Licence

The maps (`devices/`) are under [CC BY 4.0](LICENSE-DATA). If you reuse them, credit
"Modbus Register Maps by Proxus contributors" with a link to this repository. The tooling and schema are under
[Apache-2.0](LICENSE).

Register maps describe how devices communicate; vendor names and model numbers belong to their owners. Always check
a map against your device's documentation before you write to a register.
