# Server Metrics 2026-03-04 04:52:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 27717.5 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193511
telemt_connections_bad_total 1636
telemt_handshake_timeouts_total 3688
telemt_upstream_connect_attempt_total 19815
telemt_upstream_connect_success_total 19727
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 19727
telemt_upstream_connect_attempts_per_request{bucket="2"} 39
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 211
telemt_me_reconnect_attempts_total 4520
telemt_me_reconnect_success_total 4502
telemt_me_reader_eof_total 4607
telemt_me_idle_close_by_peer_total 4607
telemt_me_route_drop_no_conn_total 63465
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 524
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 6
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4607
telemt_me_writer_restored_same_endpoint_total 4482
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 183475
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 1956377992 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 59146669736 (55.08 GB)
telemt_user_unique_ips_current{user="hello"} 62
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 27714.1 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92977
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 20766
telemt_upstream_connect_attempt_total 63711
telemt_upstream_connect_success_total 63044
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 63038
telemt_upstream_connect_attempts_per_request{bucket="2"} 323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_keepalive_timeout_total 977
telemt_me_reconnect_attempts_total 39119
telemt_me_reconnect_success_total 39091
telemt_me_reader_eof_total 40080
telemt_me_idle_close_by_peer_total 40079
telemt_me_route_drop_no_conn_total 28521
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 40141
telemt_me_writer_restored_same_endpoint_total 39070
telemt_me_writer_removed_unexpected_minus_restored_total 1071
telemt_user_connections_total{user="hello"} 66431
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 612320600 (583.95 MB)
telemt_user_octets_to_client{user="hello"} 29442056824 (27.42 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 27712.9 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205387
telemt_connections_bad_total 75037
telemt_handshake_timeouts_total 4366
telemt_upstream_connect_attempt_total 36004
telemt_upstream_connect_success_total 35761
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 35761
telemt_upstream_connect_attempts_per_request{bucket="2"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 475
telemt_me_reconnect_attempts_total 14437
telemt_me_reconnect_success_total 14399
telemt_me_reader_eof_total 15152
telemt_me_idle_close_by_peer_total 15149
telemt_me_route_drop_no_conn_total 41012
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 314
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 15160
telemt_me_writer_restored_same_endpoint_total 14378
telemt_me_writer_removed_unexpected_minus_restored_total 782
telemt_user_connections_total{user="hello"} 121811
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 776781760 (740.80 MB)
telemt_user_octets_to_client{user="hello"} 31305986192 (29.16 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 27711.8 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102597
telemt_connections_bad_total 5690
telemt_handshake_timeouts_total 1185
telemt_upstream_connect_attempt_total 18894
telemt_upstream_connect_success_total 18813
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 18813
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 2970
telemt_me_reconnect_success_total 2969
telemt_me_reader_eof_total 2992
telemt_me_idle_close_by_peer_total 2992
telemt_me_route_drop_no_conn_total 33152
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 113
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 2992
telemt_me_writer_restored_same_endpoint_total 2948
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 91323
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 763741324 (728.36 MB)
telemt_user_octets_to_client{user="hello"} 30777374260 (28.66 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 27710.4 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224248
telemt_connections_bad_total 5036
telemt_handshake_timeouts_total 101545
telemt_upstream_connect_attempt_total 40705
telemt_upstream_connect_success_total 40424
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 40424
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 557
telemt_me_reconnect_attempts_total 19743
telemt_me_reconnect_success_total 19734
telemt_me_reader_eof_total 20870
telemt_me_idle_close_by_peer_total 20869
telemt_me_route_drop_no_conn_total 52528
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 118
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 158
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 20882
telemt_me_writer_restored_same_endpoint_total 19710
telemt_me_writer_removed_unexpected_minus_restored_total 1172
telemt_user_connections_total{user="hello"} 113712
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 793421588 (756.67 MB)
telemt_user_octets_to_client{user="hello"} 26463148556 (24.65 GB)
telemt_user_unique_ips_current{user="hello"} 30
```