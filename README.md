# Server Metrics 2026-03-12 07:16:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4657.4 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137721
telemt_connections_bad_total 1180
telemt_handshake_timeouts_total 1398
telemt_upstream_connect_attempt_total 1014
telemt_upstream_connect_success_total 1006
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 721
telemt_me_reconnect_success_total 718
telemt_me_reader_eof_total 715
telemt_me_idle_close_by_peer_total 715
telemt_me_route_drop_no_conn_total 45864
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 716
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 132219
telemt_user_connections_current{user="hello"} 1186
telemt_user_octets_from_client{user="hello"} 2332878668 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 41456333640 (38.61 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34277.8 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158261
telemt_connections_bad_total 2074
telemt_handshake_timeouts_total 6231
telemt_upstream_connect_attempt_total 8898
telemt_upstream_connect_success_total 8893
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 7012
telemt_me_reconnect_success_total 6974
telemt_me_reader_eof_total 7415
telemt_me_idle_close_by_peer_total 7415
telemt_me_route_drop_no_conn_total 46008
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 399
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7031
telemt_me_writer_restored_same_endpoint_total 6965
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 139264
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 2219948307 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 57730447342 (53.77 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 34277.5 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510924
telemt_connections_bad_total 2429
telemt_handshake_timeouts_total 38176
telemt_upstream_connect_attempt_total 9169
telemt_upstream_connect_success_total 9167
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 7141
telemt_me_reconnect_success_total 7074
telemt_me_reader_eof_total 7416
telemt_me_idle_close_by_peer_total 7416
telemt_me_route_drop_no_conn_total 88996
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262410
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1160
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 800
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7060
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7033
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 262702
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 2817368904 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 95278726489 (88.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 34278.1 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229262
telemt_connections_bad_total 1741
telemt_handshake_timeouts_total 14472
telemt_upstream_connect_attempt_total 9651
telemt_upstream_connect_success_total 9611
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 7910
telemt_me_reconnect_success_total 7882
telemt_me_reader_eof_total 8371
telemt_me_idle_close_by_peer_total 8371
telemt_me_route_drop_no_conn_total 74891
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187643
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 327
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7930
telemt_me_writer_restored_same_endpoint_total 7861
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 187509
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 2146740320 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 59873639616 (55.76 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34277.8 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245070
telemt_connections_bad_total 318
telemt_handshake_timeouts_total 1755
telemt_upstream_connect_attempt_total 11603
telemt_upstream_connect_success_total 11462
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 11603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 11244
telemt_me_reconnect_success_total 9732
telemt_me_reader_eof_total 10128
telemt_me_idle_close_by_peer_total 10128
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 76261
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230623
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 927
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9871
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9712
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 230577
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 2169814456 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 54662223044 (50.91 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 81
```