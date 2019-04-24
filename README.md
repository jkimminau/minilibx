# minilibx

minilibx is a 42 student made graphics library, that I like to use because it's simplicity allows for a lot of my own learning.

When digging for leaks in my fdf and fractol projects, I noticed that mlx leaked when freeing an mlx pointer initialized mlx_init(). So I added an mlx_free() function that properly frees that pointer properly.
