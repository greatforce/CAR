# CAR

## créer a catkin workspace:
1. prerequit 
 * avoir installer ros indigo
2. Créer le dossieret l'initialiser
 * mkdir -p ~/catkin_ws/src
 * cd ~/catkin_ws/src
 * catkin_init_workspace
3. Build 
 * cd ~/catkin_ws/
 * catkin_make
4. ajout setup.*sh en fonction de votre terminal
 * si vous utiliser bash
 * ajouter les lignes suivantes dans votre fichier .bashrc
 ** #ros
 ** source /opt/ros/indigo/setup.bash
 ** #catkin workspace
 ** source ~/catkin_ws/devel/setup.bash
