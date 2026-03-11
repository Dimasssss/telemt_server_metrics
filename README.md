# Server Metrics 2026-03-11 07:58:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 63068.3 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1282862
telemt_connections_bad_total 13657
telemt_handshake_timeouts_total 39568
telemt_upstream_connect_attempt_total 13078
telemt_upstream_connect_success_total 13069
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 728
telemt_me_reconnect_attempts_total 21567
telemt_me_reconnect_success_total 9882
telemt_me_reader_eof_total 10733
telemt_me_idle_close_by_peer_total 10733
telemt_me_route_drop_no_conn_total 472294
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1160971
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5703
telemt_desync_full_logged_total 1590
telemt_desync_suppressed_total 4113
telemt_desync_frames_bucket_total{bucket="1_2"} 1496
telemt_desync_frames_bucket_total{bucket="3_10"} 2166
telemt_desync_frames_bucket_total{bucket="gt_10"} 2041
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10344
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9876
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 1160625
telemt_user_connections_current{user="hello"} 1210
telemt_user_octets_from_client{user="hello"} 15174618324 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 340745600448 (317.34 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63125.1 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498571
telemt_connections_bad_total 7356
telemt_handshake_timeouts_total 28463
telemt_upstream_connect_attempt_total 22030
telemt_upstream_connect_success_total 19110
telemt_upstream_connect_fail_total 2920
telemt_upstream_connect_attempts_per_request{bucket="1"} 22030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2920
telemt_me_keepalive_timeout_total 2055
telemt_me_reconnect_attempts_total 13811
telemt_me_reconnect_success_total 12983
telemt_me_reader_eof_total 13735
telemt_me_idle_close_by_peer_total 13733
telemt_me_route_drop_no_conn_total 214265
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422832
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2093
telemt_desync_full_logged_total 642
telemt_desync_suppressed_total 1451
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13132
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12961
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 425099
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 4159582474 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 112560525392 (104.83 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 63125.0 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 836202
telemt_connections_bad_total 7084
telemt_handshake_timeouts_total 45298
telemt_upstream_connect_attempt_total 17096
telemt_upstream_connect_success_total 16885
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 17096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 743
telemt_me_reconnect_attempts_total 24984
telemt_me_reconnect_success_total 12627
telemt_me_reader_eof_total 13591
telemt_me_idle_close_by_peer_total 13591
telemt_me_route_drop_no_conn_total 284545
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 748709
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2167
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1527
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 13172
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12616
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 749496
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 8876598577 (8.27 GB)
telemt_user_octets_to_client{user="hello"} 225111081617 (209.65 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 63125.4 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 638549
telemt_connections_bad_total 59093
telemt_handshake_timeouts_total 62964
telemt_upstream_connect_attempt_total 17636
telemt_upstream_connect_success_total 17636
telemt_upstream_connect_attempts_per_request{bucket="1"} 17636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 673
telemt_me_reconnect_attempts_total 15509
telemt_me_reconnect_success_total 14457
telemt_me_reader_eof_total 15355
telemt_me_idle_close_by_peer_total 15354
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 196510
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495780
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1175
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 724
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 14627
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14435
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 495175
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 5923239552 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 136182430228 (126.83 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63125.2 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 669601
telemt_connections_bad_total 5975
telemt_handshake_timeouts_total 5443
telemt_upstream_connect_attempt_total 17486
telemt_upstream_connect_success_total 17414
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 709
telemt_me_reconnect_attempts_total 17909
telemt_me_reconnect_success_total 14121
telemt_me_reader_eof_total 14927
telemt_me_idle_close_by_peer_total 14927
telemt_me_route_drop_no_conn_total 224736
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 610397
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2790
telemt_desync_full_logged_total 1053
telemt_desync_suppressed_total 1737
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14418
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14121
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 610096
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 10136139027 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 222332194398 (207.06 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 91
```