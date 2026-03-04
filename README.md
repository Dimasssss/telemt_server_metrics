# Server Metrics 2026-03-04 05:18:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 29253.2 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214547
telemt_connections_bad_total 2305
telemt_handshake_timeouts_total 4115
telemt_upstream_connect_attempt_total 20456
telemt_upstream_connect_success_total 20363
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20363
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 4553
telemt_me_reconnect_success_total 4535
telemt_me_reader_eof_total 4640
telemt_me_idle_close_by_peer_total 4640
telemt_me_route_drop_no_conn_total 69143
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 569
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 6
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4640
telemt_me_writer_restored_same_endpoint_total 4515
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 202831
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 2121287820 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 67821138700 (63.16 GB)
telemt_user_unique_ips_current{user="hello"} 76
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 29249.9 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101356
telemt_connections_bad_total 353
telemt_handshake_timeouts_total 21381
telemt_upstream_connect_attempt_total 66015
telemt_upstream_connect_success_total 65278
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 65272
telemt_upstream_connect_attempts_per_request{bucket="2"} 358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_keepalive_timeout_total 992
telemt_me_reconnect_attempts_total 39979
telemt_me_reconnect_success_total 39951
telemt_me_reader_eof_total 40955
telemt_me_idle_close_by_peer_total 40954
telemt_me_route_drop_no_conn_total 31709
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 204
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 41016
telemt_me_writer_restored_same_endpoint_total 39930
telemt_me_writer_removed_unexpected_minus_restored_total 1086
telemt_user_connections_total{user="hello"} 73938
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 659258620 (628.72 MB)
telemt_user_octets_to_client{user="hello"} 31552175016 (29.39 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 29248.6 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225487
telemt_connections_bad_total 82939
telemt_handshake_timeouts_total 4569
telemt_upstream_connect_attempt_total 38315
telemt_upstream_connect_success_total 38064
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 38064
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 15381
telemt_me_reconnect_success_total 15341
telemt_me_reader_eof_total 16152
telemt_me_idle_close_by_peer_total 16149
telemt_me_route_drop_no_conn_total 46123
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 332
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 16160
telemt_me_writer_restored_same_endpoint_total 15320
telemt_me_writer_removed_unexpected_minus_restored_total 840
telemt_user_connections_total{user="hello"} 133542
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 971450056 (926.45 MB)
telemt_user_octets_to_client{user="hello"} 34660277980 (32.28 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 29247.8 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113316
telemt_connections_bad_total 7775
telemt_handshake_timeouts_total 1363
telemt_upstream_connect_attempt_total 20728
telemt_upstream_connect_success_total 20639
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 20639
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 3560
telemt_me_reconnect_success_total 3558
telemt_me_reader_eof_total 3597
telemt_me_idle_close_by_peer_total 3597
telemt_me_route_drop_no_conn_total 35791
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 120
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 3597
telemt_me_writer_restored_same_endpoint_total 3537
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 99625
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 849194724 (809.86 MB)
telemt_user_octets_to_client{user="hello"} 34986988432 (32.58 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 29246.2 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242134
telemt_connections_bad_total 5432
telemt_handshake_timeouts_total 108409
telemt_upstream_connect_attempt_total 43223
telemt_upstream_connect_success_total 42932
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 42932
telemt_upstream_connect_attempts_per_request{bucket="2"} 136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 588
telemt_me_reconnect_attempts_total 20811
telemt_me_reconnect_success_total 20800
telemt_me_reader_eof_total 21958
telemt_me_idle_close_by_peer_total 21957
telemt_me_route_drop_no_conn_total 55659
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 174
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 21971
telemt_me_writer_restored_same_endpoint_total 20776
telemt_me_writer_removed_unexpected_minus_restored_total 1195
telemt_user_connections_total{user="hello"} 124044
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 972000316 (926.97 MB)
telemt_user_octets_to_client{user="hello"} 28762590928 (26.79 GB)
telemt_user_unique_ips_current{user="hello"} 31
```