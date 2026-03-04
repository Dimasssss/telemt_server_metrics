# Server Metrics 2026-03-04 03:35:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 23111.2 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148057
telemt_connections_bad_total 1538
telemt_handshake_timeouts_total 2460
telemt_upstream_connect_attempt_total 17741
telemt_upstream_connect_success_total 17666
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 17666
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4268
telemt_me_reconnect_success_total 4255
telemt_me_reader_eof_total 4356
telemt_me_idle_close_by_peer_total 4356
telemt_me_route_drop_no_conn_total 50921
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 313
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4356
telemt_me_writer_restored_same_endpoint_total 4235
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 140706
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 1335702400 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 42948300024 (40.00 GB)
telemt_user_unique_ips_current{user="hello"} 65
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 23107.8 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70015
telemt_connections_bad_total 287
telemt_handshake_timeouts_total 18149
telemt_upstream_connect_attempt_total 58914
telemt_upstream_connect_success_total 58324
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 58318
telemt_upstream_connect_attempts_per_request{bucket="2"} 285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 926
telemt_me_reconnect_attempts_total 37263
telemt_me_reconnect_success_total 37239
telemt_me_reader_eof_total 38204
telemt_me_idle_close_by_peer_total 38203
telemt_me_route_drop_no_conn_total 22670
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 156
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_me_writer_removed_unexpected_total 38265
telemt_me_writer_restored_same_endpoint_total 37219
telemt_me_writer_removed_unexpected_minus_restored_total 1046
telemt_user_connections_total{user="hello"} 50753
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 420597928 (401.11 MB)
telemt_user_octets_to_client{user="hello"} 25663062508 (23.90 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 23106.5 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161250
telemt_connections_bad_total 58844
telemt_handshake_timeouts_total 3610
telemt_upstream_connect_attempt_total 31615
telemt_upstream_connect_success_total 31404
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 31404
telemt_upstream_connect_attempts_per_request{bucket="2"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 425
telemt_me_reconnect_attempts_total 13069
telemt_me_reconnect_success_total 13041
telemt_me_reader_eof_total 13705
telemt_me_idle_close_by_peer_total 13702
telemt_me_route_drop_no_conn_total 31232
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 295
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 13710
telemt_me_writer_restored_same_endpoint_total 13020
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 95252
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 594630764 (567.08 MB)
telemt_user_octets_to_client{user="hello"} 25007955036 (23.29 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 23105.4 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77324
telemt_connections_bad_total 1639
telemt_handshake_timeouts_total 697
telemt_upstream_connect_attempt_total 14801
telemt_upstream_connect_success_total 14728
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 14728
telemt_upstream_connect_attempts_per_request{bucket="2"} 36
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 2030
telemt_me_reconnect_success_total 2033
telemt_me_reader_eof_total 2044
telemt_me_idle_close_by_peer_total 2044
telemt_me_route_drop_no_conn_total 25557
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 83
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 2044
telemt_me_writer_restored_same_endpoint_total 2012
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 71708
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 645333860 (615.44 MB)
telemt_user_octets_to_client{user="hello"} 25092241408 (23.37 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 23104.0 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176118
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 80716
telemt_upstream_connect_attempt_total 35475
telemt_upstream_connect_success_total 35254
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 35254
telemt_upstream_connect_attempts_per_request{bucket="2"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 17903
telemt_me_reconnect_success_total 17896
telemt_me_reader_eof_total 18958
telemt_me_idle_close_by_peer_total 18957
telemt_me_route_drop_no_conn_total 45857
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 124
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_pool_stale_pick_total 2698
telemt_me_writer_removed_unexpected_total 18968
telemt_me_writer_restored_same_endpoint_total 17872
telemt_me_writer_removed_unexpected_minus_restored_total 1096
telemt_user_connections_total{user="hello"} 91957
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 546896460 (521.56 MB)
telemt_user_octets_to_client{user="hello"} 21213791792 (19.76 GB)
telemt_user_unique_ips_current{user="hello"} 24
```