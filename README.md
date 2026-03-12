# Server Metrics 2026-03-12 06:55:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3432.8 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98865
telemt_connections_bad_total 1179
telemt_handshake_timeouts_total 954
telemt_upstream_connect_attempt_total 692
telemt_upstream_connect_success_total 687
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 269
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 486
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 31537
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94673
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 538
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 401
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 482
telemt_me_writer_restored_same_endpoint_total 473
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 94624
telemt_user_connections_current{user="hello"} 1199
telemt_user_octets_from_client{user="hello"} 1829972340 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 30639341676 (28.54 GB)
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33053.3 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145678
telemt_connections_bad_total 1984
telemt_handshake_timeouts_total 5680
telemt_upstream_connect_attempt_total 8646
telemt_upstream_connect_success_total 8641
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 211
telemt_me_reconnect_attempts_total 6838
telemt_me_reconnect_success_total 6801
telemt_me_reader_eof_total 7233
telemt_me_idle_close_by_peer_total 7233
telemt_me_route_drop_no_conn_total 42617
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128056
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6857
telemt_me_writer_restored_same_endpoint_total 6792
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 128291
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 1979678455 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 55017387450 (51.24 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 33053.0 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486787
telemt_connections_bad_total 2324
telemt_handshake_timeouts_total 36145
telemt_upstream_connect_attempt_total 8919
telemt_upstream_connect_success_total 8917
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 6969
telemt_me_reconnect_success_total 6903
telemt_me_reader_eof_total 7236
telemt_me_idle_close_by_peer_total 7236
telemt_me_route_drop_no_conn_total 80612
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240759
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1051
telemt_desync_full_logged_total 332
telemt_desync_suppressed_total 719
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6888
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6862
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 241059
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 2648573316 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 84968891433 (79.13 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 33053.5 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214667
telemt_connections_bad_total 1738
telemt_handshake_timeouts_total 13631
telemt_upstream_connect_attempt_total 9429
telemt_upstream_connect_success_total 9389
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 7762
telemt_me_reconnect_success_total 7734
telemt_me_reader_eof_total 8216
telemt_me_idle_close_by_peer_total 8216
telemt_me_route_drop_no_conn_total 68905
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174085
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 188
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7780
telemt_me_writer_restored_same_endpoint_total 7713
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 173950
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 1966248620 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 54572444108 (50.82 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33053.2 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227917
telemt_connections_bad_total 311
telemt_handshake_timeouts_total 1430
telemt_upstream_connect_attempt_total 11197
telemt_upstream_connect_success_total 11068
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 11197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 10913
telemt_me_reconnect_success_total 9401
telemt_me_reader_eof_total 9795
telemt_me_idle_close_by_peer_total 9795
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 69998
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215719
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 852
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 333
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9537
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9382
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 215674
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 1932501144 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 49715841332 (46.30 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 104
```