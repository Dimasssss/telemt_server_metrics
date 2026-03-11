# Server Metrics 2026-03-11 07:02:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 59709.5 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188107
telemt_connections_bad_total 13289
telemt_handshake_timeouts_total 38789
telemt_upstream_connect_attempt_total 12561
telemt_upstream_connect_success_total 12552
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 706
telemt_me_reconnect_attempts_total 21198
telemt_me_reconnect_success_total 9515
telemt_me_reader_eof_total 10344
telemt_me_idle_close_by_peer_total 10344
telemt_me_route_drop_no_conn_total 436530
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1070971
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5172
telemt_desync_full_logged_total 1448
telemt_desync_suppressed_total 3724
telemt_desync_frames_bucket_total{bucket="1_2"} 1382
telemt_desync_frames_bucket_total{bucket="3_10"} 1937
telemt_desync_frames_bucket_total{bucket="gt_10"} 1853
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9973
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9509
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 1070633
telemt_user_connections_current{user="hello"} 1291
telemt_user_octets_from_client{user="hello"} 14165824800 (13.19 GB)
telemt_user_octets_to_client{user="hello"} 315289983632 (293.64 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59766.0 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458841
telemt_connections_bad_total 5705
telemt_handshake_timeouts_total 22261
telemt_upstream_connect_attempt_total 21320
telemt_upstream_connect_success_total 18406
telemt_upstream_connect_fail_total 2914
telemt_upstream_connect_attempts_per_request{bucket="1"} 21320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2914
telemt_me_keepalive_timeout_total 2032
telemt_me_reconnect_attempts_total 13279
telemt_me_reconnect_success_total 12454
telemt_me_reader_eof_total 13172
telemt_me_idle_close_by_peer_total 13170
telemt_me_route_drop_no_conn_total 205539
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392630
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1986
telemt_desync_full_logged_total 607
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 713
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12598
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12432
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 394898
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 3912769730 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 100710683012 (93.79 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 59765.9 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779194
telemt_connections_bad_total 6730
telemt_handshake_timeouts_total 42132
telemt_upstream_connect_attempt_total 16097
telemt_upstream_connect_success_total 15891
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 16097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 711
telemt_me_reconnect_attempts_total 22887
telemt_me_reconnect_success_total 11813
telemt_me_reader_eof_total 12710
telemt_me_idle_close_by_peer_total 12710
telemt_me_route_drop_no_conn_total 263559
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697058
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1974
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1399
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 798
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12308
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11802
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 697866
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 8187674613 (7.63 GB)
telemt_user_octets_to_client{user="hello"} 205318391505 (191.22 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 59766.3 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595807
telemt_connections_bad_total 56010
telemt_handshake_timeouts_total 59891
telemt_upstream_connect_attempt_total 16946
telemt_upstream_connect_success_total 16946
telemt_upstream_connect_attempts_per_request{bucket="1"} 16946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 656
telemt_me_reconnect_attempts_total 14992
telemt_me_reconnect_success_total 13944
telemt_me_reader_eof_total 14809
telemt_me_idle_close_by_peer_total 14809
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 181454
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460233
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 993
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 590
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14106
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13922
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 459664
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 5518188376 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 125947134692 (117.30 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59765.9 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618285
telemt_connections_bad_total 5966
telemt_handshake_timeouts_total 4481
telemt_upstream_connect_attempt_total 16844
telemt_upstream_connect_success_total 16774
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 16844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 681
telemt_me_reconnect_attempts_total 17443
telemt_me_reconnect_success_total 13657
telemt_me_reader_eof_total 14432
telemt_me_idle_close_by_peer_total 14432
telemt_me_route_drop_no_conn_total 204958
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563415
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2641
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 1632
telemt_desync_frames_bucket_total{bucket="1_2"} 940
telemt_desync_frames_bucket_total{bucket="3_10"} 1123
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 13950
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13657
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 563141
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 9721803495 (9.05 GB)
telemt_user_octets_to_client{user="hello"} 207152004850 (192.93 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 102
```