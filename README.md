# Server Metrics 2026-03-06 04:53:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 23526.4 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175847
telemt_connections_bad_total 15967
telemt_handshake_timeouts_total 3138
telemt_upstream_connect_attempt_total 24773
telemt_upstream_connect_success_total 24573
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 24573
telemt_upstream_connect_attempts_per_request{bucket="2"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 8986
telemt_me_reconnect_success_total 8954
telemt_me_reader_eof_total 9273
telemt_me_idle_close_by_peer_total 9273
telemt_me_route_drop_no_conn_total 50747
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 488
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9274
telemt_me_writer_restored_same_endpoint_total 8948
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 148490
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 3225195196 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 57245926588 (53.31 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 23521.8 (6h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64525
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 891
telemt_upstream_connect_attempt_total 23437
telemt_upstream_connect_success_total 23435
telemt_upstream_connect_attempts_per_request{bucket="1"} 23435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 6745
telemt_me_reconnect_success_total 6725
telemt_me_reader_eof_total 6875
telemt_me_idle_close_by_peer_total 6875
telemt_me_route_drop_no_conn_total 19218
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 266
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 7
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 71
telemt_me_writer_removed_unexpected_total 6876
telemt_me_writer_restored_same_endpoint_total 6719
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 62352
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 552419080 (526.83 MB)
telemt_user_octets_to_client{user="hello"} 16031896732 (14.93 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 23519.3 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111771
telemt_connections_bad_total 1354
telemt_handshake_timeouts_total 2554
telemt_upstream_connect_attempt_total 22432
telemt_upstream_connect_success_total 22251
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 22251
telemt_upstream_connect_attempts_per_request{bucket="2"} 80
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 268
telemt_me_reconnect_attempts_total 6924
telemt_me_reconnect_success_total 6899
telemt_me_reader_eof_total 7205
telemt_me_idle_close_by_peer_total 7205
telemt_me_route_drop_no_conn_total 31649
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 224
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 7210
telemt_me_writer_restored_same_endpoint_total 6891
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 104430
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 994955444 (948.86 MB)
telemt_user_octets_to_client{user="hello"} 34913095960 (32.52 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 23515.9 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91337
telemt_connections_bad_total 4524
telemt_handshake_timeouts_total 5259
telemt_upstream_connect_attempt_total 15786
telemt_upstream_connect_success_total 15730
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 15730
telemt_upstream_connect_attempts_per_request{bucket="2"} 27
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 2996
telemt_me_reconnect_success_total 2971
telemt_me_reader_eof_total 3078
telemt_me_idle_close_by_peer_total 3078
telemt_me_route_drop_no_conn_total 30614
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 253
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 3078
telemt_me_writer_restored_same_endpoint_total 2964
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 77100
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 1403888984 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 30151121288 (28.08 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 23514.8 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104998
telemt_connections_bad_total 1014
telemt_handshake_timeouts_total 616
telemt_upstream_connect_attempt_total 16316
telemt_upstream_connect_success_total 16279
telemt_upstream_connect_attempts_per_request{bucket="1"} 16279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6564
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 2841
telemt_me_reconnect_success_total 2829
telemt_me_reader_eof_total 2929
telemt_me_idle_close_by_peer_total 2928
telemt_me_route_drop_no_conn_total 35959
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 147
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 8
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2933
telemt_me_writer_restored_same_endpoint_total 2822
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 101579
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 23509061360 (21.89 GB)
telemt_user_octets_to_client{user="hello"} 58625726008 (54.60 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 51
```