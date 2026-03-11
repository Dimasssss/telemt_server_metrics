# Server Metrics 2026-03-11 09:50:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 69791.7 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1503520
telemt_connections_bad_total 21632
telemt_handshake_timeouts_total 40815
telemt_upstream_connect_attempt_total 14471
telemt_upstream_connect_success_total 14462
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 781
telemt_me_reconnect_attempts_total 22626
telemt_me_reconnect_success_total 10938
telemt_me_reader_eof_total 11849
telemt_me_idle_close_by_peer_total 11849
telemt_me_route_drop_no_conn_total 555000
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1364919
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6782
telemt_desync_full_logged_total 1868
telemt_desync_suppressed_total 4914
telemt_desync_frames_bucket_total{bucket="1_2"} 1786
telemt_desync_frames_bucket_total{bucket="3_10"} 2572
telemt_desync_frames_bucket_total{bucket="gt_10"} 2424
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 11409
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10932
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 1363515
telemt_user_connections_current{user="hello"} 1324
telemt_user_octets_from_client{user="hello"} 17956763624 (16.72 GB)
telemt_user_octets_to_client{user="hello"} 391267779620 (364.40 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69848.6 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576529
telemt_connections_bad_total 10175
telemt_handshake_timeouts_total 32195
telemt_upstream_connect_attempt_total 23483
telemt_upstream_connect_success_total 20554
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2110
telemt_me_reconnect_attempts_total 14951
telemt_me_reconnect_success_total 14112
telemt_me_reader_eof_total 14945
telemt_me_idle_close_by_peer_total 14943
telemt_me_route_drop_no_conn_total 239013
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489031
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2237
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1550
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14278
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14090
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 491269
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 4770092718 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 136166727428 (126.82 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 69848.4 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1003724
telemt_connections_bad_total 7604
telemt_handshake_timeouts_total 98468
telemt_upstream_connect_attempt_total 18848
telemt_upstream_connect_success_total 18617
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 18848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_timeout_total 776
telemt_me_reconnect_attempts_total 26410
telemt_me_reconnect_success_total 14042
telemt_me_reader_eof_total 15080
telemt_me_idle_close_by_peer_total 15080
telemt_me_route_drop_no_conn_total 330102
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 858425
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2478
telemt_desync_full_logged_total 730
telemt_desync_suppressed_total 1748
telemt_desync_frames_bucket_total{bucket="1_2"} 594
telemt_desync_frames_bucket_total{bucket="3_10"} 905
telemt_desync_frames_bucket_total{bucket="gt_10"} 979
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14612
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 14031
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 859300
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 10145064909 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 262224451765 (244.22 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 69848.9 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731882
telemt_connections_bad_total 65719
telemt_handshake_timeouts_total 70480
telemt_upstream_connect_attempt_total 19134
telemt_upstream_connect_success_total 19134
telemt_upstream_connect_attempts_per_request{bucket="1"} 19134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 712
telemt_me_reconnect_attempts_total 16703
telemt_me_reconnect_success_total 15649
telemt_me_reader_eof_total 16621
telemt_me_idle_close_by_peer_total 16620
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 228899
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573543
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1264
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 786
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15835
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15626
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 572917
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 6656903348 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 163558830052 (152.33 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69848.6 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777959
telemt_connections_bad_total 6078
telemt_handshake_timeouts_total 7631
telemt_upstream_connect_attempt_total 18894
telemt_upstream_connect_success_total 18817
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 18894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 780
telemt_me_reconnect_attempts_total 19007
telemt_me_reconnect_success_total 15214
telemt_me_reader_eof_total 16087
telemt_me_idle_close_by_peer_total 16087
telemt_me_route_drop_no_conn_total 266919
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705158
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2973
telemt_desync_full_logged_total 1124
telemt_desync_suppressed_total 1849
telemt_desync_frames_bucket_total{bucket="1_2"} 1040
telemt_desync_frames_bucket_total{bucket="3_10"} 1216
telemt_desync_frames_bucket_total{bucket="gt_10"} 717
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 15526
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15214
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 704842
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 11050297231 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 255708356146 (238.15 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 88
```