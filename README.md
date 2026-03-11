# Server Metrics 2026-03-11 12:43:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 80203.6 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1862254
telemt_connections_bad_total 27756
telemt_handshake_timeouts_total 47977
telemt_upstream_connect_attempt_total 16580
telemt_upstream_connect_success_total 16571
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 862
telemt_me_reconnect_attempts_total 25344
telemt_me_reconnect_success_total 12516
telemt_me_reader_eof_total 13540
telemt_me_idle_close_by_peer_total 13540
telemt_me_route_drop_no_conn_total 685446
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1698286
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8875
telemt_desync_full_logged_total 2393
telemt_desync_suppressed_total 6482
telemt_desync_frames_bucket_total{bucket="1_2"} 2203
telemt_desync_frames_bucket_total{bucket="3_10"} 3409
telemt_desync_frames_bucket_total{bucket="gt_10"} 3263
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13052
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12510
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 1696826
telemt_user_connections_current{user="hello"} 1445
telemt_user_octets_from_client{user="hello"} 22455030020 (20.91 GB)
telemt_user_octets_to_client{user="hello"} 482141876076 (449.03 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80260.4 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707684
telemt_connections_bad_total 13024
telemt_handshake_timeouts_total 49850
telemt_upstream_connect_attempt_total 26060
telemt_upstream_connect_success_total 23118
telemt_upstream_connect_fail_total 2942
telemt_upstream_connect_attempts_per_request{bucket="1"} 26060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2942
telemt_me_keepalive_timeout_total 2430
telemt_me_reconnect_attempts_total 16989
telemt_me_reconnect_success_total 16129
telemt_me_reader_eof_total 17068
telemt_me_idle_close_by_peer_total 17065
telemt_me_route_drop_no_conn_total 278919
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595247
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2668
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 1827
telemt_desync_frames_bucket_total{bucket="1_2"} 846
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 849
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 16337
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16106
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 597505
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 6418238314 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 171322344540 (159.56 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 80260.3 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1219912
telemt_connections_bad_total 8103
telemt_handshake_timeouts_total 114710
telemt_upstream_connect_attempt_total 21553
telemt_upstream_connect_success_total 21291
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 21553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 873
telemt_me_reconnect_attempts_total 30306
telemt_me_reconnect_success_total 16159
telemt_me_reader_eof_total 17340
telemt_me_idle_close_by_peer_total 17340
telemt_me_route_drop_no_conn_total 416531
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1050841
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2845
telemt_desync_full_logged_total 846
telemt_desync_suppressed_total 1999
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 1070
telemt_desync_frames_bucket_total{bucket="gt_10"} 1085
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16814
telemt_me_refill_failed_total 438
telemt_me_writer_restored_same_endpoint_total 16148
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 1051392
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 12285828209 (11.44 GB)
telemt_user_octets_to_client{user="hello"} 315578141877 (293.91 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 80260.7 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880489
telemt_connections_bad_total 75413
telemt_handshake_timeouts_total 81390
telemt_upstream_connect_attempt_total 21835
telemt_upstream_connect_success_total 21835
telemt_upstream_connect_attempts_per_request{bucket="1"} 21835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 869
telemt_me_reconnect_attempts_total 18873
telemt_me_reconnect_success_total 17807
telemt_me_reader_eof_total 18891
telemt_me_idle_close_by_peer_total 18890
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 282241
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699207
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1466
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 895
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 527
telemt_desync_frames_bucket_total{bucket="gt_10"} 411
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18023
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17780
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 698566
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 7931308740 (7.39 GB)
telemt_user_octets_to_client{user="hello"} 199805731444 (186.08 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80260.4 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 952780
telemt_connections_bad_total 6805
telemt_handshake_timeouts_total 8901
telemt_upstream_connect_attempt_total 21953
telemt_upstream_connect_success_total 21858
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 21953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 930
telemt_me_reconnect_attempts_total 21773
telemt_me_reconnect_success_total 17706
telemt_me_reader_eof_total 18684
telemt_me_idle_close_by_peer_total 18684
telemt_me_route_drop_no_conn_total 335453
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865165
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3514
telemt_desync_full_logged_total 1298
telemt_desync_suppressed_total 2216
telemt_desync_frames_bucket_total{bucket="1_2"} 1208
telemt_desync_frames_bucket_total{bucket="3_10"} 1356
telemt_desync_frames_bucket_total{bucket="gt_10"} 950
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18062
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17706
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 864919
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 12793201263 (11.91 GB)
telemt_user_octets_to_client{user="hello"} 312247994510 (290.80 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 112
```