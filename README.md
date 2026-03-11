# Server Metrics 2026-03-11 02:43:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 44161.5 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858754
telemt_connections_bad_total 10060
telemt_handshake_timeouts_total 15693
telemt_upstream_connect_attempt_total 9597
telemt_upstream_connect_success_total 9588
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 501
telemt_me_reconnect_attempts_total 18996
telemt_me_reconnect_success_total 7327
telemt_me_reader_eof_total 7999
telemt_me_idle_close_by_peer_total 7999
telemt_me_route_drop_no_conn_total 343537
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 805101
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3674
telemt_desync_full_logged_total 1038
telemt_desync_suppressed_total 2636
telemt_desync_frames_bucket_total{bucket="1_2"} 1075
telemt_desync_frames_bucket_total{bucket="3_10"} 1378
telemt_desync_frames_bucket_total{bucket="gt_10"} 1221
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 7754
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7321
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 804835
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 10899567556 (10.15 GB)
telemt_user_octets_to_client{user="hello"} 240397425656 (223.89 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44218.2 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362298
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 18218
telemt_upstream_connect_attempt_total 17264
telemt_upstream_connect_success_total 14374
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 17264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1744
telemt_me_reconnect_attempts_total 9986
telemt_me_reconnect_success_total 9169
telemt_me_reader_eof_total 9679
telemt_me_idle_close_by_peer_total 9677
telemt_me_route_drop_no_conn_total 177610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310405
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 9284
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9148
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 312675
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 2952984858 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 73184622240 (68.16 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 44217.9 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604619
telemt_connections_bad_total 4908
telemt_handshake_timeouts_total 34650
telemt_upstream_connect_attempt_total 12066
telemt_upstream_connect_success_total 11903
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 538
telemt_me_reconnect_attempts_total 19638
telemt_me_reconnect_success_total 8570
telemt_me_reader_eof_total 9306
telemt_me_idle_close_by_peer_total 9306
telemt_me_route_drop_no_conn_total 205443
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536253
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1549
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 1095
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 667
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9033
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8559
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 537153
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 7023395897 (6.54 GB)
telemt_user_octets_to_client{user="hello"} 165063583257 (153.73 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 44218.3 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454183
telemt_connections_bad_total 41821
telemt_handshake_timeouts_total 44039
telemt_upstream_connect_attempt_total 12886
telemt_upstream_connect_success_total 12886
telemt_upstream_connect_attempts_per_request{bucket="1"} 12886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 439
telemt_me_reconnect_attempts_total 11668
telemt_me_reconnect_success_total 10630
telemt_me_reader_eof_total 11270
telemt_me_idle_close_by_peer_total 11270
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 136085
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354683
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 10757
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10611
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 354352
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 4346888000 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 94745697684 (88.24 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44218.0 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478565
telemt_connections_bad_total 5791
telemt_handshake_timeouts_total 3024
telemt_upstream_connect_attempt_total 13034
telemt_upstream_connect_success_total 12978
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 13033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 528
telemt_me_reconnect_attempts_total 14460
telemt_me_reconnect_success_total 10684
telemt_me_reader_eof_total 11262
telemt_me_idle_close_by_peer_total 11262
telemt_me_route_drop_no_conn_total 154920
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436424
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2314
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 1412
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 10941
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10684
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 436091
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 8524938664 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 155747281116 (145.05 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 39
```