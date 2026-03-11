# Server Metrics 2026-03-11 12:59:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 81123.9 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1893656
telemt_connections_bad_total 27770
telemt_handshake_timeouts_total 48783
telemt_upstream_connect_attempt_total 16821
telemt_upstream_connect_success_total 16812
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 876
telemt_me_reconnect_attempts_total 25522
telemt_me_reconnect_success_total 12694
telemt_me_reader_eof_total 13720
telemt_me_idle_close_by_peer_total 13720
telemt_me_route_drop_no_conn_total 696901
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1727853
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9026
telemt_desync_full_logged_total 2440
telemt_desync_suppressed_total 6586
telemt_desync_frames_bucket_total{bucket="1_2"} 2239
telemt_desync_frames_bucket_total{bucket="3_10"} 3473
telemt_desync_frames_bucket_total{bucket="gt_10"} 3314
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13231
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12688
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 1726390
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 22817653324 (21.25 GB)
telemt_user_octets_to_client{user="hello"} 489328210428 (455.72 GB)
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81180.5 (22h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720665
telemt_connections_bad_total 13027
telemt_handshake_timeouts_total 50419
telemt_upstream_connect_attempt_total 26262
telemt_upstream_connect_success_total 23318
telemt_upstream_connect_fail_total 2944
telemt_upstream_connect_attempts_per_request{bucket="1"} 26262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2944
telemt_me_keepalive_timeout_total 2438
telemt_me_reconnect_attempts_total 17146
telemt_me_reconnect_success_total 16283
telemt_me_reader_eof_total 17236
telemt_me_idle_close_by_peer_total 17233
telemt_me_route_drop_no_conn_total 282559
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605405
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2683
telemt_desync_full_logged_total 847
telemt_desync_suppressed_total 1836
telemt_desync_frames_bucket_total{bucket="1_2"} 848
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 859
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 16492
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16260
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 607736
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 6531168746 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 174110745944 (162.15 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 81180.4 (22h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1237413
telemt_connections_bad_total 8114
telemt_handshake_timeouts_total 115176
telemt_upstream_connect_attempt_total 21757
telemt_upstream_connect_success_total 21490
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 21757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 874
telemt_me_reconnect_attempts_total 31899
telemt_me_reconnect_success_total 16311
telemt_me_reader_eof_total 17538
telemt_me_idle_close_by_peer_total 17538
telemt_me_route_drop_no_conn_total 427409
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1067801
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2882
telemt_desync_full_logged_total 860
telemt_desync_suppressed_total 2022
telemt_desync_frames_bucket_total{bucket="1_2"} 698
telemt_desync_frames_bucket_total{bucket="3_10"} 1084
telemt_desync_frames_bucket_total{bucket="gt_10"} 1100
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 17012
telemt_me_refill_failed_total 483
telemt_me_writer_restored_same_endpoint_total 16300
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 701
telemt_user_connections_total{user="hello"} 1068182
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 12570609513 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 320787600053 (298.76 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 81180.8 (22h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 893786
telemt_connections_bad_total 76247
telemt_handshake_timeouts_total 83470
telemt_upstream_connect_attempt_total 22118
telemt_upstream_connect_success_total 22118
telemt_upstream_connect_attempts_per_request{bucket="1"} 22118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 889
telemt_me_reconnect_attempts_total 19111
telemt_me_reconnect_success_total 18043
telemt_me_reader_eof_total 19135
telemt_me_idle_close_by_peer_total 19134
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 286732
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709348
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1490
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 908
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18267
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18016
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 708706
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 8042792084 (7.49 GB)
telemt_user_octets_to_client{user="hello"} 203128862844 (189.18 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81180.6 (22h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 968481
telemt_connections_bad_total 6807
telemt_handshake_timeouts_total 9004
telemt_upstream_connect_attempt_total 22129
telemt_upstream_connect_success_total 22033
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 22129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 931
telemt_me_reconnect_attempts_total 21902
telemt_me_reconnect_success_total 17835
telemt_me_reader_eof_total 18819
telemt_me_idle_close_by_peer_total 18819
telemt_me_route_drop_no_conn_total 341409
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 880084
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3561
telemt_desync_full_logged_total 1314
telemt_desync_suppressed_total 2247
telemt_desync_frames_bucket_total{bucket="1_2"} 1239
telemt_desync_frames_bucket_total{bucket="3_10"} 1364
telemt_desync_frames_bucket_total{bucket="gt_10"} 958
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18190
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17835
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 879836
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 12946760987 (12.06 GB)
telemt_user_octets_to_client{user="hello"} 316215845838 (294.50 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 110
```