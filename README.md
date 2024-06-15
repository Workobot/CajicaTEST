#  ArchiBot Web | Compo
 - Recordar que no se pueden subir archivos de mas de 100MB.
 - Organizar por carpetas para poder descargar directamente sin tener que descargar todo el repo.
 	- <a href="https://drive.google.com/file/d/1J1X-j5a1nZFUbNS5aAkLFha45s8EMPLG/view?usp=drive_link" target="_blank">Tutorial para descargar carpetas sin clonar un repo.</a>

 ---------------------------------------------------------------
01_Planning/
---------------------------------------------------------------
Acá van los archivos de planeación de las misiones de drone.

	• Planning_ConCAD.png
	• Planning_SinCAD.png
	• MiniOrtho.png
	• ...


---------------------------------------------------------------
02_DroneCapturas/
---------------------------------------------------------------
Acá van solo los frames de las misiones de drone.

!!! Todas las secuencias deben tener la misma cantidad de frames.
!!! No subir videos.

	• 02.1_Drone_Spinners/Loc_R500_A150_T20/
		• Loc_R500_A150_T20_F0001.jpg
		• ...
		• Loc_R500_A150_T20_F0060.jpg
	
	• 02.2_Drone_Vista360/Pt01_Ps01/
		• DJI_001.dng
		• DJI_002.dng
	
	• 02.3_Drone_OrthoPhoto/Ortho_A100/
		• DJI_001.jpg
		• DJI_002.jpg


---------------------------------------------------------------
03_Tracking/
---------------------------------------------------------------
Acá van los archivos 3d finales del tracking:

	• Archivo de tracking sin dependecias. (Syntheyes)
 
 	• ABC001-NombreProyecto.max
 	NOTA: Este archivo tiene todos los tracking.
	
	• Loc_R500_A150_T20.fbx
		• Loc_R500_A150_T20_F0001
		• Loc_R500_A150_T20_F0002
		NOTA: Cada cubo debe tener el eje Z mirando hacia el target.
		NOTA: Revisar la escala con unidades en metros.
	

---------------------------------------------------------------
04_Render/
---------------------------------------------------------------
Acá van los renders Albedo y Mask exportados desde Unity y la escena con todas sus dependencias de /WIP.

	• Unity/
		• ABC001-Proyecto.unitypackage.part1.rar
		• ABC001-Proyecto.unitypackage.part##.rar
		NOTA: Solo exportar lo del /WIP, nada de la librería.
	
	• Loc_R500_A150_T20_ALB/
		• Loc_R500_A150_T20_Alb_01.png
		• Loc_R500_A150_T20_Alb_02.png
		NOTA: Numerar con ceros a la izquierda.
		
	• Loc_R500_A150_T20_MASK/
		• Loc_R500_A150_T20_Mask_01.png
		• Loc_R500_A150_T20_Mask_02.png
		NOTA: Numerar con ceros a la izquierda.


---------------------------------------------------------------
05_Compo/
---------------------------------------------------------------
Acá va el archivo de compo y las secuencias en alta y en baja:

	• Loc_R500_A150_T20.aep //Compo en After
	
	• Loc_R500_A150_T20_HIGH/
		• Loc_R500_A150_T20_HIGH_1.png
		• Loc_R500_A150_T20_HIGH_60.png
  		NOTA: 4K Sin compression

	• Loc_R500_A150_T20_LOW/
		• Loc_R500_A150_T20_LOW_1.webp
		• Loc_R500_A150_T20_LOW_60.webp
		NOTA: Los renders en baja deben quedar en 2K, WebP y compresión al ##%. No pesar más de 500kb.
		NOTA: No agregar ceros a la izquierda en la numeración.
		
		
---------------------------------------------------------------
06_Vista360/
---------------------------------------------------------------
Acá va la edición de las vistas 360. Se guardan los psd y la imagen final en alta y en baja.

	• Pt01_Ps01/
		• Pt01_Ps01_stitch.jpg		
		• Pt01_Ps01_edit.psd.part1.rar
		• Pt01_Ps01_edit.psd.part##.rar
			
	• Vista360_HIGH/
		• Pt01_Ps01_HIGH.jpg
		• Pt01_Ps05_HIGH.jpg
		
	• Vista360_LOW/
		• Pt01_Ps01_LOW.webp
		• Pt01_Ps05_LOW.webp
		NOTA: Exportar a 6000x3000, WebP con peso máximo de 2MB.




