# MinecraftPE
This is a Minecraft PE I programmed in scratch, converted to .html using forkphorus.github.io

How it Works 
This uses basic 3D pen and images for the block rendering. The save codes use all the info needed for the world; inventory, entities/blocks, and their coordinates. When you enter the code, it splits it into different lists and then uses those lists to run the game.\n Beta Features, unlike the regular program, uses individual pixels with individual programs, making it very unstable and unpredictable (It is not recommended). Each block in the game equals 1 item per list in 4 different lists because the lists for the blocks/entities ask for:
-What type of item is it?
-What is its x, y, and z coordinates?
The program constantly renders the world using the lists. The loading part is just for loading list data and adding items to the lists, which is why it is so fast when its loading. The assets in the "render" sprite are for the block images.
Known Bugs
-Beta features are unstable and super glitchy.\n-sometimes 1 or even 2 blocks doesn't show up on startup.\n-on the first time you try to break a block, it may go slowly.
-Sometimes the pig flickers but doesn't show.
-The hotbar doesn't always have the best sensitivity.
Save Code Format:
(inventory) %(entity ids) (x) (y) (z)\n\nExample:\nbarrier %1 0 0 0 \nWill make a barrier in the inventory, a barrier at the coordinates 0 0 0.\nI may make an engine/tutorial to help explain.
