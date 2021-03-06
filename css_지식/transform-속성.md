> 콘텐츠 모양을 자유롭게 변형하기

| 속성명           | 속성값           | 설명                                                                                                                                           |
| ---------------- | ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| transform (2D)   | scale            | 선택한 요소의 크기를 확대·축소합니다. 현재 크기의 비율을 기준으로 1 보다 크면 확대하고, 1보다 작으면 축소합니다.                               |
|                  | skew             | 선택한 요소를 x축 또는 y축으로 비틀어서 변형합니다. 원하는 각도를 지정하여 기울기를 조절할 수 있습니다.                                        |
|                  | translate        | 선택한 요소를 현재 위치 기준에서 x축 또는 y축으로 이동할 수 있습니다.                                                                          |
|                  | rotate           | 선택한 요소를 회전시킵니다. 원하는 각도를 지정하여 회전할 수 있습니다.                                                                         |
| transform (3D)   | rotateX, rotateY | 선택한 요소를 x축 또는 y축으로 입체감 있게 회전합니다.                                                                                         |
|                  | translateZ       | 선택한 요소를 z축으로 입체감 있게 보이면서 이동시킵니다.                                                                                       |
| perspective      | px               | 3D 효과가 적용된 요소가 입체감 있게 보이도록 부모 요소에 perspective 속성을 적용하여 원근감을 부여합니다.                                      |
| transform-style  | preserve-3d      | 3D 효과가 적용된 요소에 모션 처리를 하면 해당 3D 효과가 풀리는데, 이때 부모 요소에 preserve-3d 속성을 적용하여 3D 효과를 유지시킬 수 있습니다. |
| transform-origin | 가로축, 세로축   | 요소의 변형이 일어나는 중심축을 가로축, 세로축 기준으로 변경할 수 있습니다.                                                                    |

perspective 속성값이 작을 수록 3D 요소의 왜곡이 심하게 나타나고, 값이 클수록 완만해집니다.
transform-origin 속성값을 지정하지 않으면 기본값인 center center가 자동 적용.

질문: transform의 3D 속성 외에 perspective는 왜 적용할까요?

> 이론으로는 transform의 3D 속성을 적용하면 perspective 속성값을 추가하지 않아도 입 체 효과가 나타나는 것이 맞습니다. 다만 사람이 어떤 물체를 보고 입체적이라고 느끼는 가장 큰 이유는 소실점이 생겨 공간이 왜곡되기 때문입니다. 하지만 웹 브라우저는 단지 수칫값만 으로 입체 효과를 내야 하므로 perspective 속성값을 추가하여 사람의 눈이 느끼는 왜곡 현 상을 강제로 적용해 줘야 합니다. 이때 속성값(px)은 물체를 바라보는 거리의 값이라고 이해 하면 쉽습니다. 똑같은 물체를 가까운 곳에서 보면 왜곡이 커지고, 멀리서 보면 왜곡이 완만해 지는 원리와 같습니다.
