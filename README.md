# distributedblender

The repository consists of Code that is used in this Medium article:
https://theycallmeloki.medium.com/distributed-rendering-with-pachyderm-17a6cb234384

This is essentially part 2 of my first article,
Repo: [https://github.com/theycallmeloki/splitencoder](https://github.com/theycallmeloki/splitencoder)
Article: [https://theycallmeloki.medium.com/distributed-encoding-with-pachyderm-6f79223d7a99](https://theycallmeloki.medium.com/distributed-encoding-with-pachyderm-6f79223d7a99)

There are two parts to this repo

| Type                    | Description                                                                                                  |
| ----------------------- | ------------------------------------------------------------------------------------------------------------ |
| simple-blender-renderer | Takes a `.blend` file and renders it frame by frame                                                          |
| split-blender-renderer  | Takes a `.blend` file and renders it tile by time, and finally merges the tiles back together to form frames |

Render Blender scenes with a heterogenous cluster!

Built with Pachyderm

Idea inspired by https://github.com/ccremer/clustercode/
