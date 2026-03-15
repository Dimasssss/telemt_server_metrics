# Server Metrics 2026-03-15 11:52:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 49054.3 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1330484
telemt_connections_bad_total 79622
telemt_handshake_timeouts_total 11028
telemt_upstream_connect_attempt_total 9892
telemt_upstream_connect_success_total 9847
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 10978
telemt_me_reconnect_success_total 7383
telemt_me_reader_eof_total 7889
telemt_me_idle_close_by_peer_total 7889
telemt_me_route_drop_no_conn_total 440163
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1113521
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4263
telemt_desync_full_logged_total 1210
telemt_desync_suppressed_total 3053
telemt_desync_frames_bucket_total{bucket="1_2"} 1028
telemt_desync_frames_bucket_total{bucket="3_10"} 1676
telemt_desync_frames_bucket_total{bucket="gt_10"} 1559
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7604
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7372
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 1113302
telemt_user_connections_current{user="hello"} 2230
telemt_user_octets_from_client{user="hello"} 15502658116 (14.44 GB)
telemt_user_octets_to_client{user="hello"} 446963056624 (416.27 GB)
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 49054.8 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520620
telemt_connections_bad_total 27505
telemt_handshake_timeouts_total 25677
telemt_upstream_connect_attempt_total 12850
telemt_upstream_connect_success_total 12785
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10060
telemt_me_reconnect_success_total 9994
telemt_me_reader_eof_total 10561
telemt_me_idle_close_by_peer_total 10561
telemt_me_route_drop_no_conn_total 133374
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409836
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1547
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 570
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10102
telemt_me_writer_restored_same_endpoint_total 9982
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 410106
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 5882865851 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 152938775416 (142.44 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 49054.8 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1017362
telemt_connections_bad_total 33850
telemt_handshake_timeouts_total 102857
telemt_upstream_connect_attempt_total 10875
telemt_upstream_connect_success_total 10822
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 10875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 9586
telemt_me_reconnect_success_total 8346
telemt_me_reader_eof_total 8854
telemt_me_idle_close_by_peer_total 8854
telemt_me_route_drop_no_conn_total 287889
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711920
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1801
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1168
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 725
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8493
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8327
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 710446
telemt_user_connections_current{user="hello"} 1226
telemt_user_octets_from_client{user="hello"} 10540532752 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 274220664784 (255.39 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 49054.7 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526757
telemt_connections_bad_total 64103
telemt_handshake_timeouts_total 27831
telemt_upstream_connect_attempt_total 14357
telemt_upstream_connect_success_total 13985
telemt_upstream_connect_fail_total 372
telemt_upstream_connect_attempts_per_request{bucket="1"} 14357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 372
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 36861
telemt_me_reconnect_success_total 11519
telemt_me_reader_eof_total 12646
telemt_me_idle_close_by_peer_total 12646
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 148488
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394492
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1056
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 789
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 436
telemt_desync_frames_bucket_total{bucket="gt_10"} 347
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12421
telemt_me_refill_failed_total 792
telemt_me_writer_restored_same_endpoint_total 11487
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 394389
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 4793455568 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 125943450704 (117.29 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 49056.1 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556412
telemt_connections_bad_total 6573
telemt_handshake_timeouts_total 12201
telemt_upstream_connect_attempt_total 10904
telemt_upstream_connect_success_total 10849
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 8438
telemt_me_reconnect_success_total 8392
telemt_me_reader_eof_total 8915
telemt_me_idle_close_by_peer_total 8915
telemt_me_route_drop_no_conn_total 142322
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458490
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1791
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 725
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8486
telemt_me_writer_restored_same_endpoint_total 8384
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 458525
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 6064245248 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 165799466972 (154.41 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 128
```