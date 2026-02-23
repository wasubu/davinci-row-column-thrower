# row and column thrower
![Screenshot](header.gif)
---
### Parent transform
```lua
{
	Tools = ordered() {
		Transform1 = Transform {
			CtrlWZoom = false,
			Inputs = {
				Starting = Input {
					Value = Point {
						X = 2.088109,
						Y = -0.8825231481481
					},
				},
				Center = Input {
					SourceOp = "Path1",
					Source = "Position",
				},
				Size = Input {
					Value = 0.54,
					Expression = "ModuleSize",
				},
				TimeOffset = Input { Value = 1, },
				RowColVec = Input { Value = { 0.612, -0.589 }, },
				MaxCols = Input { Value = 6, },
				ModuleSize = Input { Value = 0.54, },
				LuaDir = Input { Value = "C:\\user content\\davinci current proj\\audio chip review\\Document2 fusion.lua", },
				StartingPoint = Input { Value = { 2.719692, -1.609017 }, },
				EndPoint = Input { Value = { -1.153, 1.995 }, }
			},
			ViewInfo = OperatorInfo { Pos = { -715, 181.5 } },
			UserControls = ordered() { TimeOffset = { INP_Integer = true, ICS_ControlPage = "Controls", LINKID_DataType = "Number", INPID_InputControl = "SliderControl", INP_MinScale = 0, INP_MaxScale = 10, LINKS_Name = "TimeOffset", }, RowColVec = { INP_DefaultX = 0, INP_DefaultY = 0, LINKID_DataType = "Point", ICS_ControlPage = "Controls", INPID_InputControl = "OffsetControl", LINKS_Name = "RowColVec", }, MaxCols = { INP_MaxAllowed = 100, INP_Integer = true, INPID_InputControl = "SliderControl", INP_MaxScale = 20, INP_MinScale = 1, INP_MinAllowed = 1, LINKID_DataType = "Number", ICS_ControlPage = "Controls", LINKS_Name = "MaxCols" }, ModuleSize = { INP_MaxAllowed = 5, INP_Integer = false, INPID_InputControl = "SliderControl", IC_Steps = 0, INP_MaxScale = 5, INP_Default = 1, INP_MinScale = 0.100000001490116, INP_MinAllowed = 0.100000001490116, LINKID_DataType = "Number", ICS_ControlPage = "Controls", ICD_Center = 1, LINKS_Name = "ModuleSize" }, LuaDir = { INP_External = false, LINKID_DataType = "Text", ICS_ControlPage = "Controls", INPID_InputControl = "FileControl", LINKS_Name = "LuaDir", }, StartingPoint = { LINKS_Name = "StartingPoint", LINKID_DataType = "Point", INPID_InputControl = "OffsetControl", ICS_ControlPage = "Controls", }, EndPoint = { LINKS_Name = "EndPoint", LINKID_DataType = "Point", INPID_InputControl = "OffsetControl", ICS_ControlPage = "Controls", } }
		},
		Path1 = PolyPath {
			DrawMode = "ClickAppend",
			CtrlWZoom = false,
			Inputs = {
				Displacement = Input {
					SourceOp = "Path1Displacement",
					Source = "Value",
				},
				PolyLine = Input {
					Value = Polyline {
						Points = {
							{ Linear = true, LockY = true, X = 2.21969177352843, Y = -2.10901675609756, RX = -1.29089725784281, RY = 1.20133891869919 },
							{ Linear = true, LockY = true, X = -1.653, Y = 1.495, LX = 1.29089725784281, LY = -1.20133891869919 }
						}
					},
				}
			},
		},
		Path1Displacement = BezierSpline {
			SplineColor = { Red = 255, Green = 0, Blue = 255 },
			KeyFrames = {
				[0] = { 0, RH = { 7.32841041352707, 0.644977076826085 }, Flags = { LockedY = true } },
				[22] = { 1, LH = { 13.6506064093566, 1 }, Flags = { LockedY = true } }
			}
		}
	},
	ActiveTool = "Transform1"
}
```
