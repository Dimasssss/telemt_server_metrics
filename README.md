# Server Metrics 2026-03-15 12:38:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 51811.8 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466773
telemt_connections_bad_total 86204
telemt_handshake_timeouts_total 12550
telemt_upstream_connect_attempt_total 10315
telemt_upstream_connect_success_total 10267
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12546
telemt_me_reconnect_success_total 7667
telemt_me_reader_eof_total 8228
telemt_me_idle_close_by_peer_total 8228
telemt_me_route_drop_no_conn_total 491318
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1231264
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4632
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 3327
telemt_desync_frames_bucket_total{bucket="1_2"} 1138
telemt_desync_frames_bucket_total{bucket="3_10"} 1816
telemt_desync_frames_bucket_total{bucket="gt_10"} 1678
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7934
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7656
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 1230931
telemt_user_connections_current{user="hello"} 2344
telemt_user_octets_from_client{user="hello"} 17346653528 (16.16 GB)
telemt_user_octets_to_client{user="hello"} 491274737324 (457.54 GB)
telemt_user_unique_ips_current{user="hello"} 631
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 51812.6 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587625
telemt_connections_bad_total 29761
telemt_handshake_timeouts_total 37803
telemt_upstream_connect_attempt_total 13452
telemt_upstream_connect_success_total 13385
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 13452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10525
telemt_me_reconnect_success_total 10450
telemt_me_reader_eof_total 11048
telemt_me_idle_close_by_peer_total 11048
telemt_me_route_drop_no_conn_total 148714
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452943
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1773
telemt_desync_full_logged_total 620
telemt_desync_suppressed_total 1153
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 649
telemt_desync_frames_bucket_total{bucket="gt_10"} 451
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10568
telemt_me_writer_restored_same_endpoint_total 10438
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 453210
telemt_user_connections_current{user="hello"} 677
telemt_user_octets_from_client{user="hello"} 6386759675 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 167942603932 (156.41 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 51812.5 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1185604
telemt_connections_bad_total 39047
telemt_handshake_timeouts_total 120672
telemt_upstream_connect_attempt_total 11455
telemt_upstream_connect_success_total 11399
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10031
telemt_me_reconnect_success_total 8786
telemt_me_reader_eof_total 9321
telemt_me_idle_close_by_peer_total 9321
telemt_me_route_drop_no_conn_total 357572
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788638
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2026
telemt_desync_full_logged_total 723
telemt_desync_suppressed_total 1303
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 751
telemt_desync_frames_bucket_total{bucket="gt_10"} 822
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 8937
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8767
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 785130
telemt_user_connections_current{user="hello"} 1242
telemt_user_octets_from_client{user="hello"} 11532146024 (10.74 GB)
telemt_user_octets_to_client{user="hello"} 294616520024 (274.38 GB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 51812.5 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584347
telemt_connections_bad_total 66385
telemt_handshake_timeouts_total 32938
telemt_upstream_connect_attempt_total 19678
telemt_upstream_connect_success_total 19284
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 19678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 41163
telemt_me_reconnect_success_total 11708
telemt_me_reader_eof_total 12962
telemt_me_idle_close_by_peer_total 12962
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 164671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431397
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1138
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 851
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12739
telemt_me_refill_failed_total 921
telemt_me_writer_restored_same_endpoint_total 11676
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1031
telemt_user_connections_total{user="hello"} 436236
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 8435680999 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 156837375765 (146.07 GB)
telemt_user_msgs_from_client{user="hello"} 64932
telemt_user_msgs_to_client{user="hello"} 471602
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 51813.6 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627826
telemt_connections_bad_total 7451
telemt_handshake_timeouts_total 13240
telemt_upstream_connect_attempt_total 11610
telemt_upstream_connect_success_total 11549
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 9992
telemt_me_reconnect_success_total 8949
telemt_me_reader_eof_total 9518
telemt_me_idle_close_by_peer_total 9518
telemt_me_route_drop_no_conn_total 156377
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508966
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1968
telemt_desync_full_logged_total 651
telemt_desync_suppressed_total 1317
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 779
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9089
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8941
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 508997
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 6582440956 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 182350376892 (169.83 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 117
```