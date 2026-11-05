# Signalfern 1.0 TEST
Native Java/Canvas Android 8+ Shingoki-style measured-arm circle-loop puzzle.

Draw one closed non-branching loop through every circle. White circles must go straight and black circles must turn. Each number is the sum of the two straight arm lengths leaving its circle, measured in edges until the next turns. Other circles do not stop an arm. Blank dots may be unused. Tap halfway between neighboring cell centers to switch an edge. Twelve unique 4x4 clue boards have twelve distinct loops.

Saved signal palette and circle labels, GG007 icon/menu/site/privacy, unlimited undo/reset. Offline, no ads, analytics, requested permissions or account. Settings and completion marks stay on device. External studio link opens browser.

Independent Python DFS enumerates all 213 simple cycles on the 4x4 cell-center graph. A Java ordered-coordinate arm oracle checks all cycles plus 20000 random 24-edge masks per board against production edge-ray, degree and floodfill validation, confirming one solution each. Bounds, toggle, solve, undo and replay pass. Adapter menu, settings, privacy, edge taps, next, levels and persistence pass. Actual drawing-code pixels inspected, not phone screenshots. Phone runtime, performance and browser handoff QA incomplete. Signed TEST only, not final or Play published.

Registry803, 91 recovered READMEs and recent cumulative stage/release records found no Shingoki match. Shared circle straight/turn and single-loop backbone with Pearlmere Masyu is disclosed. This replaces Masyu neighboring-dot turn conditions with measured straight-arm sums, and black circles may have immediate neighboring turns. Unlike Brindlepath Yajilin, there are no arrow rays or isolated off-loop dark cells. Known Shingoki genre, not a global invention. Full prior local corpus was lost; no ALL-local scan claimed. Rules https://www.janko.at/Raetsel/Shingoki/index.htm .

Build JDK17/platform35/buildtools35, min26/target35. Signing environment placeholders, no credentials.
Download https://mega.nz/file/VBFF0TST#FBBWEdwPgnSH9K2PgaYCiNm-ySigy5s6HcRy3kQ7zW4
SHA256 `3bb855974e63ca07559756e94e272b2ccb9bb2458d53101f44b3deb7e8d8cfd2`
Full source privately preserved; Git source upload pending. APK not in repo.
