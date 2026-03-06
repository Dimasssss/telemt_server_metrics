# Server Metrics 2026-03-06 19:31:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 5017.1 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124592
telemt_connections_bad_total 1380
telemt_handshake_timeouts_total 4098
telemt_upstream_connect_attempt_total 6480
telemt_upstream_connect_success_total 6407
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 242
telemt_me_reconnect_attempts_total 1887
telemt_me_reconnect_success_total 1875
telemt_me_reader_eof_total 2385
telemt_me_idle_close_by_peer_total 2385
telemt_me_route_drop_no_conn_total 50435
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 514
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 148
telemt_me_writer_removed_unexpected_total 2405
telemt_me_writer_restored_same_endpoint_total 1869
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 109305
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 1928637476 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 36088718800 (33.61 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 5017.0 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45155
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 2321
telemt_upstream_connect_attempt_total 8648
telemt_upstream_connect_success_total 8646
telemt_upstream_connect_attempts_per_request{bucket="1"} 8646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 2942
telemt_me_reconnect_success_total 2937
telemt_me_reader_eof_total 3880
telemt_me_idle_close_by_peer_total 3880
telemt_me_route_drop_no_conn_total 16241
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 165
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 3880
telemt_me_writer_restored_same_endpoint_total 2935
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 40034
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 884809320 (843.82 MB)
telemt_user_octets_to_client{user="hello"} 11819008404 (11.01 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 5016.9 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80907
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 942
telemt_upstream_connect_attempt_total 5386
telemt_upstream_connect_success_total 5366
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 894
telemt_me_reconnect_success_total 893
telemt_me_reader_eof_total 1159
telemt_me_idle_close_by_peer_total 1159
telemt_me_route_drop_no_conn_total 25662
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 407
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 312
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 3
telemt_pool_force_close_total 88
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 1161
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 75535
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 3308414616 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 21077916692 (19.63 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 5017.4 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100010
telemt_connections_bad_total 39637
telemt_handshake_timeouts_total 4876
telemt_upstream_connect_attempt_total 6981
telemt_upstream_connect_success_total 6962
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 2035
telemt_me_reconnect_success_total 2028
telemt_me_reader_eof_total 2620
telemt_me_idle_close_by_peer_total 2620
telemt_me_route_drop_no_conn_total 17593
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 70
telemt_pool_stale_pick_total 308
telemt_me_writer_removed_unexpected_total 2620
telemt_me_writer_restored_same_endpoint_total 2024
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 53529
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 492724316 (469.90 MB)
telemt_user_octets_to_client{user="hello"} 17880612684 (16.65 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 5015.9 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73895
telemt_connections_bad_total 441
telemt_handshake_timeouts_total 416
telemt_upstream_connect_attempt_total 7077
telemt_upstream_connect_success_total 7055
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2121
telemt_me_reconnect_success_total 2116
telemt_me_reader_eof_total 3012
telemt_me_idle_close_by_peer_total 3011
telemt_me_route_drop_no_conn_total 26768
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 416
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 2
telemt_pool_force_close_total 106
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3016
telemt_me_writer_restored_same_endpoint_total 2114
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 69886
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 8322199728 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 27768068520 (25.86 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 57
```