# Server Metrics 2026-03-15 09:59:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 42310.9 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 981599
telemt_connections_bad_total 54044
telemt_handshake_timeouts_total 7535
telemt_upstream_connect_attempt_total 8415
telemt_upstream_connect_success_total 8378
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6320
telemt_me_reconnect_success_total 6284
telemt_me_reader_eof_total 6654
telemt_me_idle_close_by_peer_total 6654
telemt_me_route_drop_no_conn_total 323032
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 828312
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2985
telemt_desync_full_logged_total 860
telemt_desync_suppressed_total 2125
telemt_desync_frames_bucket_total{bucket="1_2"} 699
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 1110
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6375
telemt_me_writer_restored_same_endpoint_total 6273
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 828323
telemt_user_connections_current{user="hello"} 2006
telemt_user_octets_from_client{user="hello"} 11997741976 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 319690342584 (297.73 GB)
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 42311.5 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387013
telemt_connections_bad_total 21630
telemt_handshake_timeouts_total 15287
telemt_upstream_connect_attempt_total 11240
telemt_upstream_connect_success_total 11182
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 11240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8814
telemt_me_reconnect_success_total 8757
telemt_me_reader_eof_total 9266
telemt_me_idle_close_by_peer_total 9266
telemt_me_route_drop_no_conn_total 98255
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306396
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1083
telemt_desync_full_logged_total 375
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 359
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8839
telemt_me_writer_restored_same_endpoint_total 8749
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 306684
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 4454298259 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 115854070360 (107.90 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 42311.7 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708113
telemt_connections_bad_total 23834
telemt_handshake_timeouts_total 71340
telemt_upstream_connect_attempt_total 9350
telemt_upstream_connect_success_total 9310
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 7247
telemt_me_reconnect_success_total 7201
telemt_me_reader_eof_total 7624
telemt_me_idle_close_by_peer_total 7624
telemt_me_route_drop_no_conn_total 202559
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536878
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1165
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 732
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 421
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7292
telemt_me_writer_restored_same_endpoint_total 7182
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 536304
telemt_user_connections_current{user="hello"} 1158
telemt_user_octets_from_client{user="hello"} 8015909320 (7.47 GB)
telemt_user_octets_to_client{user="hello"} 214967722388 (200.20 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 42311.5 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407437
telemt_connections_bad_total 54133
telemt_handshake_timeouts_total 24790
telemt_upstream_connect_attempt_total 12955
telemt_upstream_connect_success_total 12640
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 12955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 29521
telemt_me_reconnect_success_total 10538
telemt_me_reader_eof_total 11445
telemt_me_idle_close_by_peer_total 11445
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 112052
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305333
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 737
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 556
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11224
telemt_me_refill_failed_total 593
telemt_me_writer_restored_same_endpoint_total 10508
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 686
telemt_user_connections_total{user="hello"} 305244
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 3624297648 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 98426484272 (91.67 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 42312.3 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396022
telemt_connections_bad_total 4425
telemt_handshake_timeouts_total 4895
telemt_upstream_connect_attempt_total 9443
telemt_upstream_connect_success_total 9400
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 7338
telemt_me_reconnect_success_total 7302
telemt_me_reader_eof_total 7759
telemt_me_idle_close_by_peer_total 7759
telemt_me_route_drop_no_conn_total 104868
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330142
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1263
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 858
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7381
telemt_me_writer_restored_same_endpoint_total 7294
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 330146
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 4063257900 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 121532970724 (113.19 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 110
```