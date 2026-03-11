# Server Metrics 2026-03-11 08:03:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 63373.7 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1292314
telemt_connections_bad_total 13664
telemt_handshake_timeouts_total 39657
telemt_upstream_connect_attempt_total 13165
telemt_upstream_connect_success_total 13156
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 729
telemt_me_reconnect_attempts_total 21630
telemt_me_reconnect_success_total 9945
telemt_me_reader_eof_total 10804
telemt_me_idle_close_by_peer_total 10804
telemt_me_route_drop_no_conn_total 476156
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1170082
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5754
telemt_desync_full_logged_total 1605
telemt_desync_suppressed_total 4149
telemt_desync_frames_bucket_total{bucket="1_2"} 1511
telemt_desync_frames_bucket_total{bucket="3_10"} 2187
telemt_desync_frames_bucket_total{bucket="gt_10"} 2056
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10409
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9939
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1169734
telemt_user_connections_current{user="hello"} 1291
telemt_user_octets_from_client{user="hello"} 15396979616 (14.34 GB)
telemt_user_octets_to_client{user="hello"} 342551610864 (319.03 GB)
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63430.6 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 501842
telemt_connections_bad_total 7411
telemt_handshake_timeouts_total 28541
telemt_upstream_connect_attempt_total 22099
telemt_upstream_connect_success_total 19179
telemt_upstream_connect_fail_total 2920
telemt_upstream_connect_attempts_per_request{bucket="1"} 22099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2920
telemt_me_keepalive_timeout_total 2056
telemt_me_reconnect_attempts_total 13880
telemt_me_reconnect_success_total 13052
telemt_me_reader_eof_total 13811
telemt_me_idle_close_by_peer_total 13809
telemt_me_route_drop_no_conn_total 215137
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425899
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2121
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1474
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 769
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13201
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13030
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 428165
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 4183015178 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 113976022404 (106.15 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 63430.4 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 841884
telemt_connections_bad_total 7085
telemt_handshake_timeouts_total 45717
telemt_upstream_connect_attempt_total 17227
telemt_upstream_connect_success_total 17016
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 17227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 746
telemt_me_reconnect_attempts_total 25115
telemt_me_reconnect_success_total 12758
telemt_me_reader_eof_total 13724
telemt_me_idle_close_by_peer_total 13724
telemt_me_route_drop_no_conn_total 286658
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753742
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2184
telemt_desync_full_logged_total 643
telemt_desync_suppressed_total 1541
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 792
telemt_desync_frames_bucket_total{bucket="gt_10"} 882
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 13305
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12747
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 754525
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 8914736605 (8.30 GB)
telemt_user_octets_to_client{user="hello"} 227156336725 (211.56 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 63430.8 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642599
telemt_connections_bad_total 59369
telemt_handshake_timeouts_total 63197
telemt_upstream_connect_attempt_total 17715
telemt_upstream_connect_success_total 17715
telemt_upstream_connect_attempts_per_request{bucket="1"} 17715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 673
telemt_me_reconnect_attempts_total 15588
telemt_me_reconnect_success_total 14536
telemt_me_reader_eof_total 15444
telemt_me_idle_close_by_peer_total 15443
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 198154
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499286
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1219
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 762
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 14708
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14514
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 498680
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 5941702724 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 137074848488 (127.66 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63430.5 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674584
telemt_connections_bad_total 5975
telemt_handshake_timeouts_total 5686
telemt_upstream_connect_attempt_total 17588
telemt_upstream_connect_success_total 17516
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 710
telemt_me_reconnect_attempts_total 18011
telemt_me_reconnect_success_total 14223
telemt_me_reader_eof_total 15029
telemt_me_idle_close_by_peer_total 15029
telemt_me_route_drop_no_conn_total 226589
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614760
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2796
telemt_desync_full_logged_total 1056
telemt_desync_suppressed_total 1740
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1170
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14520
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14223
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 614455
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 10166973771 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 224093571686 (208.70 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 110
```