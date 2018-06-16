# Frame

## Geodetic

## ECEF
 * Eearth Centered Earth Fixed
## NED
 * North East Down
 * 구와 데카르트 좌표 사이에 변환
    * python utm library 이용
 * utm 
    * utm으로 지구상에 데카르트 좌표를 매핑하는 것이 일반적
    * 지구 표면을 여러 지역으로 나눈다.
    * 동서 방향 : 60개 zone (숫자)
    * 남북 : 24개 zone (알파벳)
₩₩₩python
(easting, northing, zone_number, zone_letter) = utm.from_latlon(latitude, longitude)
(latitude, longitude) = utm.to_latlon(easting, northing, zone_number, zone_letter)
₩₩₩₩

## Body Frame
## Euler Frame
## Rotation Matrices
## Euler Rotations
## Quaternions
