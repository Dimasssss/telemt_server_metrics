# Server Metrics 2026-03-14 08:12:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 180813.5 (50h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5115830
telemt_connections_bad_total 42257
telemt_handshake_timeouts_total 116105
telemt_upstream_connect_attempt_total 38018
telemt_upstream_connect_success_total 37770
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 38018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 7401
telemt_me_reconnect_attempts_total 37672
telemt_me_reconnect_success_total 26462
telemt_me_reader_eof_total 28404
telemt_me_idle_close_by_peer_total 28403
telemt_me_route_drop_no_conn_total 1936143
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4690964
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17889
telemt_desync_full_logged_total 4872
telemt_desync_suppressed_total 13017
telemt_desync_frames_bucket_total{bucket="1_2"} 4458
telemt_desync_frames_bucket_total{bucket="3_10"} 6792
telemt_desync_frames_bucket_total{bucket="gt_10"} 6639
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 27195
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26449
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 733
telemt_user_connections_total{user="hello"} 4692400
telemt_user_connections_current{user="hello"} 1647
telemt_user_octets_from_client{user="hello"} 72012714096 (67.07 GB)
telemt_user_octets_to_client{user="hello"} 1501920789545 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80477.5 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881815
telemt_connections_bad_total 53910
telemt_handshake_timeouts_total 16236
telemt_upstream_connect_attempt_total 21651
telemt_upstream_connect_success_total 21372
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 21651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 2173
telemt_me_reconnect_attempts_total 18802
telemt_me_reconnect_success_total 15332
telemt_me_reader_eof_total 16285
telemt_me_idle_close_by_peer_total 16284
telemt_me_route_drop_no_conn_total 292263
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 710748
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2139
telemt_desync_full_logged_total 666
telemt_desync_suppressed_total 1473
telemt_desync_frames_bucket_total{bucket="1_2"} 467
telemt_desync_frames_bucket_total{bucket="3_10"} 929
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15664
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 15324
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 712656
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 7479387441 (6.97 GB)
telemt_user_octets_to_client{user="hello"} 247159330332 (230.19 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 210434.1 (58h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3654597
telemt_connections_bad_total 43209
telemt_handshake_timeouts_total 239792
telemt_upstream_connect_attempt_total 47531
telemt_upstream_connect_success_total 47510
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10764
telemt_me_reconnect_attempts_total 41725
telemt_me_reconnect_success_total 36742
telemt_me_reader_eof_total 39018
telemt_me_idle_close_by_peer_total 39017
telemt_me_route_drop_no_conn_total 1252949
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3050841
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10003
telemt_desync_full_logged_total 3371
telemt_desync_suppressed_total 6632
telemt_desync_frames_bucket_total{bucket="1_2"} 1759
telemt_desync_frames_bucket_total{bucket="3_10"} 3620
telemt_desync_frames_bucket_total{bucket="gt_10"} 4624
telemt_pool_swap_total 198
telemt_me_writer_removed_unexpected_total 37252
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36701
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 3049980
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 51645879096 (48.10 GB)
telemt_user_octets_to_client{user="hello"} 1092137651641 (1017.13 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 210436.8 (58h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2429892
telemt_connections_bad_total 23324
telemt_handshake_timeouts_total 295484
telemt_upstream_connect_attempt_total 65421
telemt_upstream_connect_success_total 62925
telemt_upstream_connect_fail_total 2359
telemt_upstream_connect_attempts_per_request{bucket="1"} 65147
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2358
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20571
telemt_me_reconnect_attempts_total 54532
telemt_me_reconnect_success_total 45450
telemt_me_reader_eof_total 48701
telemt_me_idle_close_by_peer_total 48694
telemt_me_route_drop_no_conn_total 815668
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1911328
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3936
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 2653
telemt_desync_frames_bucket_total{bucket="1_2"} 1087
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46125
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45426
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 675
telemt_user_connections_total{user="hello"} 1917446
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 28703740399 (26.73 GB)
telemt_user_octets_to_client{user="hello"} 698677789290 (650.69 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79870.2 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 860806
telemt_connections_bad_total 9347
telemt_handshake_timeouts_total 10149
telemt_upstream_connect_attempt_total 20235
telemt_upstream_connect_success_total 19693
telemt_upstream_connect_fail_total 542
telemt_upstream_connect_attempts_per_request{bucket="1"} 20235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 542
telemt_me_keepalive_timeout_total 1613
telemt_me_reconnect_attempts_total 66252
telemt_me_reconnect_success_total 15722
telemt_me_reader_eof_total 17674
telemt_me_idle_close_by_peer_total 17673
telemt_me_route_drop_no_conn_total 330186
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 803297
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2030
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1386
telemt_desync_frames_bucket_total{bucket="1_2"} 648
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17436
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15717
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1714
telemt_user_connections_total{user="hello"} 803154
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 14312350972 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 269275796364 (250.78 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 89
```