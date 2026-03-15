# Server Metrics 2026-03-15 12:53:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 52730.9 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1511850
telemt_connections_bad_total 87855
telemt_handshake_timeouts_total 13316
telemt_upstream_connect_attempt_total 10485
telemt_upstream_connect_success_total 10437
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12671
telemt_me_reconnect_success_total 7789
telemt_me_reader_eof_total 8356
telemt_me_idle_close_by_peer_total 8356
telemt_me_route_drop_no_conn_total 508590
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1271184
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4759
telemt_desync_full_logged_total 1345
telemt_desync_suppressed_total 3414
telemt_desync_frames_bucket_total{bucket="1_2"} 1177
telemt_desync_frames_bucket_total{bucket="3_10"} 1873
telemt_desync_frames_bucket_total{bucket="gt_10"} 1709
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8062
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7778
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 1270834
telemt_user_connections_current{user="hello"} 2381
telemt_user_octets_from_client{user="hello"} 17883005636 (16.65 GB)
telemt_user_octets_to_client{user="hello"} 507505744128 (472.65 GB)
telemt_user_unique_ips_current{user="hello"} 647
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 52731.8 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608593
telemt_connections_bad_total 30811
telemt_handshake_timeouts_total 39047
telemt_upstream_connect_attempt_total 13628
telemt_upstream_connect_success_total 13558
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10656
telemt_me_reconnect_success_total 10578
telemt_me_reader_eof_total 11190
telemt_me_idle_close_by_peer_total 11190
telemt_me_route_drop_no_conn_total 153117
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465634
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1819
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1184
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 667
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10701
telemt_me_writer_restored_same_endpoint_total 10566
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 465901
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 6561677975 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 172420060376 (160.58 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 52731.8 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1229783
telemt_connections_bad_total 40357
telemt_handshake_timeouts_total 124721
telemt_upstream_connect_attempt_total 11644
telemt_upstream_connect_success_total 11588
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10174
telemt_me_reconnect_success_total 8928
telemt_me_reader_eof_total 9466
telemt_me_idle_close_by_peer_total 9466
telemt_me_route_drop_no_conn_total 365828
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 814481
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2098
telemt_desync_full_logged_total 756
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 841
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9082
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8909
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 810976
telemt_user_connections_current{user="hello"} 1289
telemt_user_octets_from_client{user="hello"} 11953845752 (11.13 GB)
telemt_user_octets_to_client{user="hello"} 303055922936 (282.24 GB)
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 52731.7 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610409
telemt_connections_bad_total 67096
telemt_handshake_timeouts_total 33643
telemt_upstream_connect_attempt_total 34422
telemt_upstream_connect_success_total 34016
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 34421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 42572
telemt_me_reconnect_success_total 11741
telemt_me_reader_eof_total 13038
telemt_me_idle_close_by_peer_total 13038
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 165684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433572
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1144
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 856
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12815
telemt_me_refill_failed_total 964
telemt_me_writer_restored_same_endpoint_total 11709
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1074
telemt_user_connections_total{user="hello"} 453067
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 8633492293 (8.04 GB)
telemt_user_octets_to_client{user="hello"} 160494070598 (149.47 GB)
telemt_user_msgs_from_client{user="hello"} 315630
telemt_user_msgs_to_client{user="hello"} 1341579
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 52732.5 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 648309
telemt_connections_bad_total 8168
telemt_handshake_timeouts_total 13433
telemt_upstream_connect_attempt_total 11785
telemt_upstream_connect_success_total 11723
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 11400
telemt_me_reconnect_success_total 9076
telemt_me_reader_eof_total 9684
telemt_me_idle_close_by_peer_total 9684
telemt_me_route_drop_no_conn_total 161298
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526331
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2018
telemt_desync_full_logged_total 673
telemt_desync_suppressed_total 1345
telemt_desync_frames_bucket_total{bucket="1_2"} 582
telemt_desync_frames_bucket_total{bucket="3_10"} 806
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9256
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9068
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 526364
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 6788399356 (6.32 GB)
telemt_user_octets_to_client{user="hello"} 192091611684 (178.90 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 117
```