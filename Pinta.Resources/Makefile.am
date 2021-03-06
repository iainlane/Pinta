include $(top_srcdir)/Makefile.include

ASSEMBLY = Pinta.Resources
TARGET = library

REFERENCES = \
	-r:System \
	$(GTK_SHARP_20_LIBS) \
	$(GLIB_SHARP_20_LIBS)

SOURCES =  \
	ResourceManager.cs \
	AssemblyInfo.cs 

RESOURCES = \
	Resources/Tools.CloneStamp.png \
	Resources/Tools.FreeformShape.png \
	Resources/Tools.Line.png \
	Resources/Tools.Rectangle.png \
	Resources/Tools.RoundedRectangle.png \
	Resources/Tools.Text.png \
	Resources/Tools.LassoSelect.png \
	Resources/Tools.MagicWand.png \
	Resources/Tools.MoveSelection.png \
	Resources/Tools.Move.png \
	Resources/Tools.PaintBucket.png \
	Resources/Tools.Pan.png \
	Resources/Tools.Pencil.png \
	Resources/Tools.Recolor.png \
	Resources/Tools.RectangleSelect.png \
	Resources/Tools.Zoom.png \
	Resources/Tools.EllipseSelect.png \
	Resources/Tools.Eraser.png \
	Resources/Tools.Gradient.png \
	Resources/Tools.ColorPicker.png \
	Resources/Tools.Ellipse.png \
	Resources/LayersWidget.Visible.png \
	Resources/LayersWidget.Hidden.png \
	Resources/Toolbar.MinusButton.png \
	Resources/Toolbar.PlusButton.png \
	Resources/ColorPalette.SwapIcon.png \
	Resources/Tools.Paintbrush.png \
	Resources/StatusBar.CursorXY.png \
	Resources/Menu.Layers.AddNewLayer.png \
	Resources/Menu.Layers.DeleteLayer.png \
	Resources/Menu.Layers.DuplicateLayer.png \
	Resources/Menu.Layers.MergeLayerDown.png \
	Resources/Menu.Layers.MoveLayerDown.png \
	Resources/Menu.Layers.MoveLayerUp.png \
	Resources/Pinta.png \
	Resources/Menu.Edit.Deselect.png \
	Resources/Menu.Layers.FlipHorizontal.png \
	Resources/Menu.Layers.FlipVertical.png \
	Resources/Menu.Layers.ImportFromFile.png \
	Resources/Menu.Edit.EraseSelection.png \
	Resources/Menu.Edit.FillSelection.png \
	Resources/Menu.Edit.InvertSelection.png \
	Resources/Menu.Edit.SelectAll.png \
	Resources/Menu.View.ActualSize.png \
	Resources/Menu.View.Grid.png \
	Resources/Menu.View.Rulers.png \
	Resources/Menu.View.ZoomIn.png \
	Resources/Menu.View.ZoomOut.png \
	Resources/Menu.View.ZoomToSelection.png \
	Resources/Menu.View.ZoomToWindow.png \
	Resources/Menu.Image.CanvasSize.png \
	Resources/Menu.Image.Crop.png \
	Resources/Menu.Image.Flatten.png \
	Resources/Menu.Image.FlipHorizontal.png \
	Resources/Menu.Image.FlipVertical.png \
	Resources/Menu.Image.Resize.png \
	Resources/Menu.Image.Rotate180CW.png \
	Resources/Menu.Image.Rotate90CCW.png \
	Resources/Menu.Image.Rotate90CW.png \
	Resources/Menu.Layers.LayerProperties.png \
	Resources/Menu.Layers.RotateZoom.png \
	Resources/Menu.Adjustments.AutoLevel.png \
	Resources/Menu.Adjustments.BlackAndWhite.png \
	Resources/Menu.Adjustments.BrightnessAndContrast.png \
	Resources/Menu.Adjustments.Curves.png \
	Resources/Menu.Adjustments.HueAndSaturation.png \
	Resources/Menu.Adjustments.InvertColors.png \
	Resources/Menu.Adjustments.Levels.png \
	Resources/Menu.Adjustments.Sepia.png \
	Resources/Menu.Help.Bug.png \
	Resources/Menu.Help.Website.png \
	Resources/ResizeCanvas.Image.png \
	Resources/ResizeCanvas.DownArrow.png \
	Resources/ResizeCanvas.LeftArrow.png \
	Resources/ResizeCanvas.RightArrow.png \
	Resources/ResizeCanvas.UpArrow.png \
	Resources/ResizeCanvas.NorthEast.png \
	Resources/ResizeCanvas.NorthWest.png \
	Resources/ResizeCanvas.SouthEast.png \
	Resources/ResizeCanvas.SouthWest.png \
	Resources/Menu.Adjustments.Posterize.png \
	Resources/Toolbar.Bold.png \
	Resources/Toolbar.CenterAlignment.png \
	Resources/Toolbar.Italic.png \
	Resources/Toolbar.LeftAlignment.png \
	Resources/Toolbar.RightAlignment.png \
	Resources/Toolbar.Underline.png \
	Resources/Menu.Effects.Artistic.InkSketch.png \
	Resources/Menu.Effects.Artistic.OilPainting.png \
	Resources/Menu.Effects.Artistic.PencilSketch.png \
	Resources/Menu.Effects.Blurs.Fragment.png \
	Resources/Menu.Effects.Blurs.GaussianBlur.png \
	Resources/Menu.Effects.Blurs.MotionBlur.png \
	Resources/Menu.Effects.Blurs.RadialBlur.png \
	Resources/Menu.Effects.Blurs.SurfaceBlur.png \
	Resources/Menu.Effects.Blurs.Unfocus.png \
	Resources/Menu.Effects.Blurs.ZoomBlur.png \
	Resources/Menu.Effects.Photo.Glow.png \
	Resources/Menu.Effects.Photo.RedEyeRemove.png \
	Resources/Menu.Effects.Photo.Sharpen.png \
	Resources/Menu.Effects.Photo.SoftenPortrait.png \
	Resources/Menu.Effects.Stylize.EdgeDetect.png \
	Resources/Menu.Effects.Render.Clouds.png \
	Resources/Menu.Effects.Render.JuliaFractal.png \
	Resources/Menu.Effects.Render.MandelbrotFractal.png \
	Resources/Menu.Effects.Distort.Bulge.png \
	Resources/Menu.Effects.Noise.Median.png \
	Resources/Menu.Effects.Noise.ReduceNoise.png \
	Resources/Menu.Effects.Noise.AddNoise.png \
	Resources/Menu.Effects.Stylize.Outline.png \
	Resources/Menu.Effects.Distort.Dents.png \
	Resources/Menu.Effects.Distort.PolarInversion.png \
	Resources/Menu.Effects.Distort.Twist.png \
	Resources/Menu.Effects.Distort.Tile.png \
	Resources/Menu.Effects.Distort.Pixelate.png \
	Resources/Menu.Effects.Distort.FrostedGlass.png \
	Resources/Menu.Effects.Stylize.Relief.png \
	Resources/Menu.Effects.Stylize.Emboss.png \
	Resources/Toolbar.ConicalGradient.png \
	Resources/Toolbar.DiamondGradient.png \
	Resources/Toolbar.LinearGradient.png \
	Resources/Toolbar.LinearReflectedGradient.png \
	Resources/Toolbar.RadialGradient.png \
	Resources/Toolbar.AntiAliasingDisabledIcon.png \
	Resources/Toolbar.AntiAliasingEnabledIcon.png \
	Resources/Toolbar.BlendingEnabledIcon.png \
	Resources/Toolbar.BlendingOverwriteIcon.png \
	Resources/ShapeTool.OutlineFill.png \
	Resources/About.Image.png \
	Resources/About.ImageSep.png \
	Resources/About.MonoPowered.png \
	Resources/About.ImageTop.png \
	Resources/Menu.Help.Translate.png \
	Resources/ShapeTool.Fill.png \
	Resources/ShapeTool.Outline.png \
	Resources/Toolbar.ColorMode.png \
	Resources/Toolbar.TransparentMode.png

