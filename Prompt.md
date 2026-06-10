# The Prompt

> This is the exact prompt used across all nine models in the one-shot physics engine benchmark.  
> `[model name]` was replaced with each model's actual interface name. Everything else was identical.

---

```
You are [model name]. You have:

* Adaptive Thinking always enabled: Think deeply, step-by-step, reflect on your
  reasoning, critique your own output, and iterate before finalizing.
* Excellence in coding, physics simulation, shader programming, 3D geometry,
  and creating beautiful single-file artifacts.
* Access to tools/computer use where available — use them proactively if needed.

Core rules for this session:
1. Maximum Effort Mode: Treat this as the most important project you've ever
   worked on. Use your full intelligence, creativity, and rigor.
2. Iterative Perfection: Plan thoroughly → Execute → Self-critique → Refine → Validate.
3. Breakthrough Thinking: Challenge assumptions and aim for elegant, novel, stable solutions.
4. Output Quality: Deliver production-ready, heavily commented, visually stunning results.

Create a single, complete, self-contained HTML file that implements a real-time
3D physics simulation with complex geometry using WebGL2 (vanilla, no external libraries).

Focus: Complex geometry physics — support rigid and/or soft bodies with non-trivial
meshes (tetrahedral decomposition, convex polyhedra, or simple manifold meshes).

Core requirements:
* Procedurally generate or define complex 3D shapes (e.g. Stanford Bunny-like mesh,
  irregular polyhedra, stacked objects, or a ragdoll-like figure).
* Implement solid physics: rigid body dynamics with proper collision detection/response
  for complex geometry (GJK, SAT, or tetrahedral-based), OR a tetrahedral mass-spring /
  finite-element soft body system for deformable objects.
* Features: Gravity, friction, restitution, mouse orbit camera + click-and-drag
  to throw/apply forces.
* Visuals: Phong/Blinn lighting, basic shadows, wireframe toggle, colorful materials,
  particle effects on impacts/breaks.
* UI: Sliders for gravity, stiffness (soft bodies), damping, simulation speed;
  presets like "Rigid Stack Collapse", "Soft Bunny Drop", "Tetrahedral Chain",
  "Complex Polyhedra Destruction".
* Responsive full-window canvas, FPS counter, pause/play, reset, on-screen instructions.
* Performance: Stable and smooth (aim for 30-60fps).

Style: Visually impressive scientific/artistic hybrid — mesmerizing deformable and
rigid objects interacting with nice lighting and camera controls.

Deliver only the full HTML code inside one markdown code block (`html ... `).
Heavily comment the key physics, geometry, and shader sections.
Use adaptive thinking throughout.
```

---

**Methodology note:** Each model was accessed via its primary public interface on June 9–10, 2026.  
No system prompts were used beyond the task description above.  
No follow-up prompts were issued — whatever the model produced on the first response is what was evaluated.
