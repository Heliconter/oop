cmake_minimum_required(VERSION 3.15)
project(sem4_oop_game)

set(CMAKE_CXX_STANDARD 17)

link_libraries(raylib)

add_executable(sem4_oop_game main.cpp Units/BaseUnit.hpp Field/Field.cpp Field/Field.hpp TwoDimensionalArray.hpp Units/Unit.hpp Game.cpp Game.hpp Gui/Gui.cpp Gui/Gui.hpp Units/Knights/HeavyKnightUnit.hpp FieldPosition.hpp Units/Knights/KnightUnit.hpp Units/Knights/LightweightKnightUnit.hpp Units/Archers/ArcherUnit.hpp Units/Archers/PowerfulArcherUnit.hpp Units/Archers/DistanceArcherUnit.hpp Units/Mages/MageUnit.hpp Units/Mages/IceMageUnit.hpp Units/Mages/FireMageUnit.hpp Field/FieldIterator.cpp Field/FieldIterator.hpp Units/UnitFactory.hpp Units/ConcreteUnitFactory.hpp Gui/GuiConstants.hpp Gui/NewUnitSelectionScreen.cpp Gui/NewUnitSelectionScreen.hpp Gui/GuiTools.cpp Gui/GuiTools.hpp Gui/UnitInfoScreen.cpp Gui/UnitInfoScreen.hpp Terrains/Terrain.hpp Terrains/GroundTerrain.hpp Terrains/WaterTerrain.hpp Terrains/StoneTerrain.hpp Field/FieldCell.cpp Field/FieldCell.hpp Terrains/TerrainFactory.hpp Terrains/ConcreteTerrainFactory.hpp Units/BaseUnit.cpp)
