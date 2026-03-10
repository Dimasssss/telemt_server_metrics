# Server Metrics 2026-03-10 19:56:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19754.8 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603884
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 5393
telemt_upstream_connect_attempt_total 3937
telemt_upstream_connect_success_total 3928
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 13348
telemt_me_reconnect_success_total 2886
telemt_me_reader_eof_total 3233
telemt_me_idle_close_by_peer_total 3233
telemt_me_route_drop_no_conn_total 253301
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570058
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3024
telemt_desync_full_logged_total 811
telemt_desync_suppressed_total 2213
telemt_desync_frames_bucket_total{bucket="1_2"} 824
telemt_desync_frames_bucket_total{bucket="3_10"} 1152
telemt_desync_frames_bucket_total{bucket="gt_10"} 1048
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3229
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2880
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 569881
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 8263995756 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 165486159508 (154.12 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19811.3 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259178
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 16595
telemt_upstream_connect_attempt_total 9433
telemt_upstream_connect_success_total 6686
telemt_upstream_connect_fail_total 2747
telemt_upstream_connect_attempts_per_request{bucket="1"} 9433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1884
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2747
telemt_me_keepalive_timeout_total 718
telemt_me_reconnect_attempts_total 4469
telemt_me_reconnect_success_total 3679
telemt_me_reader_eof_total 3834
telemt_me_idle_close_by_peer_total 3832
telemt_me_route_drop_no_conn_total 141408
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222069
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1153
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 840
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3748
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3658
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 223369
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 2361441770 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 55085106074 (51.30 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 19811.2 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432463
telemt_connections_bad_total 1424
telemt_handshake_timeouts_total 32385
telemt_upstream_connect_attempt_total 6060
telemt_upstream_connect_success_total 5968
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 6060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 8271
telemt_me_reconnect_success_total 3889
telemt_me_reader_eof_total 4145
telemt_me_idle_close_by_peer_total 4145
telemt_me_route_drop_no_conn_total 148805
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373233
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1206
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 409
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4097
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 3878
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 374181
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 5410989693 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 117106268681 (109.06 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 19811.9 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289103
telemt_connections_bad_total 19581
telemt_handshake_timeouts_total 25371
telemt_upstream_connect_attempt_total 5316
telemt_upstream_connect_success_total 5316
telemt_upstream_connect_attempts_per_request{bucket="1"} 5316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 5314
telemt_me_reconnect_success_total 4298
telemt_me_reader_eof_total 4499
telemt_me_idle_close_by_peer_total 4499
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 94656
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232641
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 631
telemt_desync_full_logged_total 255
telemt_desync_suppressed_total 376
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4371
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4285
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 232346
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 3619317488 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 70646490028 (65.79 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19811.3 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304241
telemt_connections_bad_total 881
telemt_handshake_timeouts_total 1988
telemt_upstream_connect_attempt_total 6220
telemt_upstream_connect_success_total 6197
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 6220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 5192
telemt_me_reconnect_success_total 5153
telemt_me_reader_eof_total 5296
telemt_me_idle_close_by_peer_total 5296
telemt_me_route_drop_no_conn_total 111808
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286933
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1601
telemt_desync_full_logged_total 595
telemt_desync_suppressed_total 1006
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5233
telemt_me_writer_restored_same_endpoint_total 5153
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 286852
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 5582183056 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 95595395956 (89.03 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 73
```