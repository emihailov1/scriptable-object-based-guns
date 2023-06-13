# ScriptableObject-Based Gun System
Learn how to create a ScriptableObject-based gun system from scratch for your game! 

In this tutorial repository and accompanying [video series](https://www.youtube.com/watch?v=E-vIMamyORg&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to), you'll learn how to make a configuration-driven gun system with ScriptableObjects that will be able to have:
* Hitscan Guns - [Implemented in Part 1](https://www.youtube.com/watch?v=E-vIMamyORg&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=1)
* Simple Bullet Spread & Recoil - [Implemented in Part 1](https://www.youtube.com/watch?v=E-vIMamyORg&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=1).
* Simple Procedural Recoil - [Implemented in Part 2](https://www.youtube.com/watch?v=pwq7F5DeQnI&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=2)
* Procedural Recoil based on Texture - [Implemented in Part 2](https://www.youtube.com/watch?v=pwq7F5DeQnI&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=2)
* Simple Impact Damage - [Implemented in Part 3](https://www.youtube.com/watch?v=6yvUmSxlGQo&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=3) with `IDamageable` System for damaging arbitrary objects including enemies.
* Reloading - [Implemented in Part 4](https://www.youtube.com/watch?v=Tn8RYWnEd94&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=4)
* Sound Effects - [Implemented in Part 5](https://www.youtube.com/watch?v=hV3BAw2c9Io&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=5)
* Projectile Guns - [Implemented in Part 6](https://www.youtube.com/watch?v=LIB7uGDZou0&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=6)
* Accurate Aiming / Crosshairs - [Implemented in Part 7](https://www.youtube.com/watch?v=x8ECpNWMmag&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=7&pp=sAQB)
* Attachments - [Modifier System in Part 8](https://www.youtube.com/watch?v=RbIk6VnwHnI&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=8) + Attachments UI & Applying to a Gun in [Part 10](https://www.youtube.com/watch?v=8wBEb2l0vZQ&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=10)
* Animated Models - Coming with a Future Video
* Damage Effects such as burning, freezing, explosions, etc... - [Implemented in Part 9](https://www.youtube.com/watch?v=Y-Qr6GPN2v0&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=9) with `ICollisionHandler`
* Gun & Ammo Pick-ups - [Implemented in Part 11](https://www.youtube.com/watch?v=Fpt9xA3Ftmo&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to&index=11)
* And even more! - Coming with a Future Video

Impact Effects _are not_ in scope of this tutorial series. They are handled using the [Surface Manager](https://github.com/llamacademy/surface-manager) (tutorial [video here](https://youtu.be/kT2ZxjMuT_4)).

[![Youtube Tutorial](./Video%20Screenshot.jpg)](https://www.youtube.com/watch?v=E-vIMamyORg&list=PLllNmP7eq6TQJjgKJ6FKcNFfRREe_L6to)

## Quickstart
If you're following along with the tutorial series, check out the appropriate branch for the video you're watching. `main` will be the latest version and each branch such as `part-1` will be where a particular video ended.

Make sure to import the [Unity Particle Pack](https://assetstore.unity.com/packages/essentials/tutorial-projects/unity-particle-pack-127325) after checking out this repository for all the bullet shooting and impact effects.

You can import just the folder "EffectExamples" and ignore the rest of the files. This will prevent overriding all your project settings.

As of April 4, 2023, this uses [Assembly Definitions](https://docs.unity3d.com/Manual/ScriptCompilationAssemblyDefinitionFiles.html) ([tutorial](https://youtu.be/qprZHOPu2OI)) to package the files. If you are using Assembly Definition files in your project, you may need to add references to `LlamAcademy.Guns`, `LlamAcademy.ImpactSystem`, and if you choose to use the demo scripts, `LlamAcademy.Guns.Demo`.

## Supporters
Have you been getting value out of these tutorials? Do you believe in LlamAcademy's mission of helping everyone make their game dev dream become a reality? Consider becoming a Patreon supporter and get your name added to this list, as well as other cool perks.
Head over to https://patreon.com/llamacademy to show your support.

If you'd prefer to become a [YouTube Member](https://www.youtube.com/channel/UCnWm6pMD38R1E2vCAByGb6w/join) you can get all the same benefits on that platform!

### Phenomenal Supporter Tier
* Andrew Bowen
* YOUR NAME HERE!

### Tremendous Supporter Tier
* Bruno Bozic
* YOUR NAME HERE!

### Awesome Supporter Tier
* AudemKay
* Matt Parkin
* Ivan
* Reulan
* Iffy Obelus
* Dwarf
* YOUR NAME HERE!

### Supporters
* Trey Briggs
* Matt Sponholz
* Dr Bash
* Tarik
* Sean
* ag10g
* Elijah Singer
* Lurking Ninja
* Josh Meyer
* Ewald Schulte
* Dom C
* Andrew Allbright
* AudemKay
* Claduiu Barsan-Pipu
* Sschmeil22
* Ben
* Xuul
* YOUR NAME HERE!

## Other Projects
Interested in AI Topics in Unity, or other tutorials on Unity in general? 

* [Check out the LlamAcademy YouTube Channel](https://youtube.com/c/LlamAcademy)!
* [Check out the LlamAcademy GitHub for more projects](https://github.com/llamacademy)

## Socials
* [YouTube](https://youtube.com/c/LlamAcademy)
* [Facebook](https://facebook.com/LlamAcademyOfficial)
* [TikTok](https://www.tiktok.com/@llamacademy)
* [Twitter](https://twitter.com/TheLlamAcademy)
* [Instagram](https://www.instagram.com/llamacademy/)
* [Reddit](https://www.reddit.com/user/LlamAcademyOfficial)

## Requirements
* Requires Unity 2021.3 LTS or higher.
* [Unity Particle Pack](https://assetstore.unity.com/packages/essentials/tutorial-projects/unity-particle-pack-127325)
* [Surface Manager](https://github.com/llamacademy/surface-manager) - Included in this repository, but not covered in the tutorial series. Tutorial [video here](https://youtu.be/kT2ZxjMuT_4)).